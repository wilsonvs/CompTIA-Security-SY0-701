# Gestão de Risco

## Objetivos
- 5.2 - Explicar os elementos do processo de gestão de risco
- 5.3 - Explicar os processos associados à avaliação e gestão de risco de terceiros
- 5.4 - Resumir os elementos de uma conformidade de segurança eficaz

## Sumário

1. [Gestão de Risco](#gestão-de-risco)
2. [Ameaças, Vulnerabilidades e Risco](#ameaças-vulnerabilidades-e-risco)
3. [Probabilidade e Impacto](#probabilidade-e-impacto)
4. [Tipos de Risco](#tipos-de-risco)
5. [Estratégias de Resposta ao Risco](#estratégias-de-resposta-ao-risco)
6. [Registro de Riscos (Risk Register)](#registro-de-riscos-risk-register)
7. [Análise de Risco](#análise-de-risco)
8. [Análise de Impacto no Negócio](#análise-de-impacto-no-negócio)
9. [Principais Conclusões](#principais-conclusões)

## Gestão de Risco

- **Gestão de Risco:** O processo de identificar, analisar, priorizar, tratar e monitorar riscos.
- O objetivo da gestão de risco não é eliminar todo o risco. O objetivo é entender o risco com clareza e reduzi-lo a um nível aceitável.
- As equipes de segurança usam a gestão de risco para decidir o que deve ser corrigido primeiro, o que pode esperar e o que exige aprovação da liderança.

## Ameaças, Vulnerabilidades e Risco

- **Ativo (Asset):** Qualquer coisa de valor que precisa de proteção, como dados, servidores, notebooks, contas de usuário, armazenamento em nuvem, aplicações ou processos de negócio.
- **Ameaça (Threat):** Qualquer coisa que possa causar dano, perda, avaria, divulgação, interrupção ou comprometimento.
- **Vulnerabilidade:** Uma fraqueza que pode ser explorada por uma ameaça.
- **Risco:** A possibilidade de que uma ameaça explore uma vulnerabilidade e cause impacto a um ativo ou organização.

Exemplo:
- Ativo: servidor de folha de pagamento
- Ameaça: atacante externo
- Vulnerabilidade: correção de segurança ausente (patch)
- Risco: atacante explora a vulnerabilidade e acessa dados de folha de pagamento

## Probabilidade e Impacto

- **Probabilidade (Likelihood):** Quão provável é que um evento de risco aconteça.
- **Impacto:** A quantidade de dano causada caso o evento de risco aconteça.
- O impacto pode incluir:
  - Perda financeira
  - Indisponibilidade (downtime)
  - Perda de dados
  - Consequências legais ou regulatórias
  - Dano à reputação
  - Impacto à segurança das pessoas

- Um evento de alta probabilidade e alto impacto geralmente deve ser tratado como alta prioridade.
- Um evento de baixa probabilidade e baixo impacto pode ser aceito ou monitorado.

## Tipos de Risco

- **Risco Inerente:** Risco que existe antes da aplicação de controles de segurança.
- **Risco Residual:** Risco que permanece após a aplicação dos controles.
- **Risco de Controle:** Risco de que um controle falhe ou não funcione corretamente.
- **Apetite ao Risco (Risk Appetite):** A quantidade de risco que uma organização está disposta a aceitar.
- **Tolerância ao Risco (Risk Tolerance):** A variação aceitável em relação ao apetite ao risco definido.

Exemplo:
- Se uma empresa ativa o MFA, o risco de comprometimento de conta é reduzido, mas não eliminado. O risco que permanece é o risco residual.

## Estratégias de Resposta ao Risco

- **Aceitar (Accept):** Reconhecer o risco e não tomar nenhuma ação adicional além do monitoramento.
  - Exemplo: aceitar uma vulnerabilidade de baixo risco em um sistema interno não crítico.

- **Evitar (Avoid):** Interromper a atividade que cria o risco.
  - Exemplo: remover um serviço voltado ao público que não tem mais suporte.

- **Transferir (Transfer):** Transferir parte da responsabilidade ou do impacto financeiro para outra parte.
  - Exemplo: seguro cibernético ou terceirização de um serviço com requisitos contratuais de segurança.

- **Mitigar (Mitigate):** Reduzir a probabilidade ou o impacto usando controles.
  - Exemplo: aplicação de patches, MFA, criptografia, monitoramento, segmentação ou backups.

## Registro de Riscos (Risk Register)

- **Registro de Riscos:** Documento usado para rastrear os riscos identificados, a responsabilidade, o tratamento e o status.
- Um registro de riscos ajuda as equipes de segurança a comunicar o risco com clareza e acompanhar a correção.

Campos comuns de um registro de riscos:
- ID do risco
- Ativo ou sistema afetado
- Descrição do risco
- Ameaça
- Vulnerabilidade
- Probabilidade
- Impacto
- Classificação do risco
- Controles existentes
- Tratamento recomendado
- Responsável pelo risco (risk owner)
- Prazo
- Status

## Análise de Risco

- **Análise Qualitativa de Risco:** Usa classificações descritivas, como baixo, médio e alto.
- **Análise Quantitativa de Risco:** Usa números, valores monetários, probabilidades e fórmulas para estimar o risco.

Fórmulas comuns de risco:
- **SLE (Single Loss Expectancy):** Expectativa de Perda Única
- **ARO (Annualized Rate of Occurrence):** Taxa Anualizada de Ocorrência
- **ALE (Annualized Loss Expectancy):** Expectativa de Perda Anualizada

Fórmula:
- ALE = SLE x ARO

Exemplo:
- Se uma interrupção custa US$ 10.000 e é esperada duas vezes por ano, o ALE é US$ 20.000.

## Análise de Impacto no Negócio

- **Análise de Impacto no Negócio (BIA - Business Impact Analysis):** Identifica funções de negócio críticas e o impacto de uma interrupção.
- A BIA ajuda a determinar as prioridades de recuperação.

Termos importantes de BIA:
- **RTO (Recovery Time Objective):** Objetivo de Tempo de Recuperação; quão rápido um sistema deve ser restaurado.
- **RPO (Recovery Point Objective):** Objetivo de Ponto de Recuperação; quanta perda de dados é aceitável.
- **MTD (Maximum Tolerable Downtime):** Tempo Máximo Tolerável de Indisponibilidade; maior interrupção aceitável.

## Principais Conclusões

- O risco existe quando ameaças, vulnerabilidades e ativos de valor se encontram.
- O risco nem sempre pode ser eliminado, mas pode ser reduzido, transferido, evitado ou aceito.
- A gestão de risco apoia decisões melhores porque conecta problemas técnicos ao impacto no negócio.
