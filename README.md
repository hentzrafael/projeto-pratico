# Projeto Prático de Gerência de Configuração de Software

### **Professor**: Guilherme Henrique Piasson

### **Acadêmico**: Rafael Augusto Hentz

# Versionamento Semântico (SemVer)

O **versionamento semântico** é um padrão para definir versões de software de forma consistente e previsível.  
Ele segue o formato:

## Componentes

- **MAJOR** (versão principal)  
  Incrementado quando ocorrem mudanças **incompatíveis** com versões anteriores.  
  Exemplo: alterar a API de forma que o código existente que a usa quebre.

- **MINOR** (versão secundária)  
  Incrementado quando são adicionadas novas funcionalidades de forma **retrocompatível**.  
  Exemplo: adicionar uma nova função ou endpoint sem alterar os existentes.

- **PATCH** (correção)  
  Incrementado quando são feitas **correções de bugs** ou pequenas melhorias que não afetam compatibilidade.  
  Exemplo: corrigir um erro em uma função sem mudar sua interface.

## Exemplos

- `1.0.0` → Versão inicial estável.
- `1.1.0` → Adiciona funcionalidades sem quebrar compatibilidade.
- `1.1.1` → Corrige um bug sem alterar funcionalidades.
- `2.0.0` → Mudanças que quebram compatibilidade com a versão 1.x.x.

## Benefícios

- Clareza para desenvolvedores e usuários sobre o impacto da atualização.
- Facilidade para gerenciar dependências em projetos.
- Ajuda a automatizar atualizações em sistemas de controle de pacotes.

## Regras adicionais

- Prefixos como `alpha`, `beta`, `rc` (release candidate) podem ser usados:
  - `1.0.0-alpha` → versão experimental.
  - `1.0.0-beta` → versão em testes.
  - `1.0.0-rc.1` → release candidate (candidato à versão final).
