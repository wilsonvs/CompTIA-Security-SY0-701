# Fundamentos de Segurança

## Objetivos
- 1.1 - Comparar e contrastar diversos tipos de controles de segurança
- 1.2 - Resumir os conceitos fundamentais de segurança
- Entender a tríade CIA, o AAA, o não repúdio e o Zero Trust

## Sumário

1. [Segurança da Informação](#segurança-da-informação)
2. [Tríade CIA](#tríade-cia)
3. [Não Repúdio](#não-repúdio)
4. [Autenticação, Autorização e Auditoria (Accounting)](#autenticação-autorização-e-auditoria-accounting)
5. [Categorias de Controles de Segurança](#categorias-de-controles-de-segurança)
6. [Tipos de Controles de Segurança](#tipos-de-controles-de-segurança)
7. [Ameaças, Vulnerabilidades e Risco](#ameaças-vulnerabilidades-e-risco)
8. [Análise de Gaps](#análise-de-gaps)
9. [Zero Trust](#zero-trust)
10. [Principais Conclusões](#principais-conclusões)

## Segurança da Informação

- **Segurança da Informação:** Proteção de dados e informações contra acesso não autorizado, divulgação, modificação, interrupção ou destruição.
- **Segurança de Sistemas de Informação:** Proteção de sistemas que armazenam, processam ou transmitem informações.

Exemplos:
- Proteger registros de clientes
- Proteger servidores e endpoints
- Restringir o acesso a pastas sensíveis
- Monitorar logs em busca de atividades suspeitas

## Tríade CIA

- **Confidencialidade:** Garante que a informação só seja acessível a usuários autorizados.
  - Exemplo: criptografia, controle de acesso, mascaramento de dados.

- **Integridade:** Garante que os dados permaneçam precisos, completos e inalterados, a menos que modificados por um usuário autorizado.
  - Exemplo: hashing, checksums, assinaturas digitais.

- **Disponibilidade:** Garante que sistemas e dados estejam acessíveis quando necessário.
  - Exemplo: redundância, backups, failover, recuperação de desastres.

## Não Repúdio

- **Não Repúdio:** Fornece prova de que uma ação ou transação não pode ser negada posteriormente.
- Assinaturas digitais são comumente usadas para não repúdio.

Exemplo:
- Se um usuário assina digitalmente um documento, a assinatura ajuda a provar quem assinou e que o documento não foi alterado.

## Autenticação, Autorização e Contabilidade/Auditoria (Accounting)

- **Autenticação:** Verifica a identidade.
- **Autorização:** Determina quais acessos são permitidos.
- **Contabilidade/Auditoria (Accounting):** Registra as ações do usuário para logs, auditorias e investigações.

Exemplo:
- Fazer login com senha e MFA é autenticação.
- Acessar apenas as pastas designadas é autorização.
- Logs do sistema mostrando acesso a arquivos é Contabilidade/Auditoria (accounting).

## Categorias de Controles de Segurança

- **Controles Técnicos:** Controles baseados em tecnologia.
  - Exemplo: firewall, criptografia, MFA.

- **Controles Gerenciais:** Controles administrativos ou de governança.
  - Exemplo: avaliação de risco, política de segurança, auditoria.

- **Controles Operacionais:** Processos de segurança do dia a dia.
  - Exemplo: conscientização de segurança, resposta a incidentes, gestão de mudanças.

- **Controles Físicos:** Controles que protegem ativos físicos.
  - Exemplo: fechaduras, câmeras, seguranças, crachás.

## Tipos de Controles de Segurança

- **Preventivo:** Impede que um evento aconteça.
- **Detectivo:** Identifica um evento ou atividade suspeita.
- **Corretivo:** Corrige ou restaura após um evento.
- **Dissuasivo (Deterrent):** Desencoraja comportamentos indesejados.
- **Compensatório:** Controle alternativo usado quando o controle preferido não pode ser aplicado.
- **Diretivo:** Informa aos usuários o que é esperado.

## Ameaças, Vulnerabilidades e Risco

- **Ameaça:** Qualquer coisa que possa causar dano.
- **Vulnerabilidade:** Uma fraqueza que pode ser explorada.
- **Risco:** A possibilidade de que uma ameaça explore uma vulnerabilidade e cause impacto.

Exemplo:
- Ameaça: atacante
- Vulnerabilidade: servidor sem correção (patch)
- Risco: comprometimento do servidor

## Análise de Gaps

- **Análise de Gaps:** Comparação entre o estado atual e o estado desejado.
- Usada para identificar o que está faltando ou fraco.

Exemplo:
- Estado atual: sem MFA em contas de administrador.
- Estado desejado: MFA obrigatório para todas as contas de administrador.
- Gap: falta MFA para administradores.

## Zero Trust

- **Zero Trust:** Modelo de segurança baseado em nunca confiar por padrão e sempre verificar.

Ideias centrais:
- Verificar identidade
- Usar privilégio mínimo (least privilege)
- Monitorar continuamente
- Segmentar o acesso
- Assumir que houve violação (assume breach)

## Principais Conclusões

- A tríade CIA é a base da segurança.
- O AAA explica a atividade de identidade e acesso.
- Os controles de segurança devem ser aplicados em camadas para prevenir, detectar e corrigir problemas de segurança.
