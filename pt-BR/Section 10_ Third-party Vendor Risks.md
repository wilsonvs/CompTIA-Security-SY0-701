# Riscos de Fornecedores Terceirizados

## Objetivos
- 5.3 - Explicar os processos associados à avaliação e gestão de risco de terceiros
- Entender os riscos de segurança de fornecedores, provedores e cadeia de suprimentos
- Saber o que deve ser revisado antes de conceder acesso a terceiros

## Sumário

1. [Risco de Terceiros](#risco-de-terceiros)
2. [Risco da Cadeia de Suprimentos](#risco-da-cadeia-de-suprimentos)
3. [Due Diligence de Fornecedores](#due-diligence-de-fornecedores)
4. [Contratos e SLAs de Fornecedores](#contratos-e-slas-de-fornecedores)
5. [Controle de Acesso para Fornecedores](#controle-de-acesso-para-fornecedores)
6. [Monitoramento Contínuo](#monitoramento-contínuo)
7. [Offboarding de Fornecedores](#offboarding-de-fornecedores)
8. [Principais Conclusões](#principais-conclusões)

## Risco de Terceiros

- **Risco de Terceiros:** Risco criado quando um fornecedor externo, provedor, prestador de serviço, provedor de nuvem, fornecedor de software ou provedor de serviços gerenciados dá suporte às operações de negócio.
- Fornecedores podem precisar de acesso a sistemas, dados, redes, prédios ou recursos em nuvem.
- Esse acesso pode criar risco de segurança se o fornecedor tiver controles fracos.

Exemplos de terceiros:
- Provedor de serviço em nuvem
- Provedor de folha de pagamento
- Provedor de serviços de TI gerenciados
- Fornecedor de software
- Empresa de processamento de dados
- Prestador de serviço ou consultor
- Fornecedor de hardware

## Risco da Cadeia de Suprimentos

- **Risco da Cadeia de Suprimentos:** Risco proveniente de produtos, serviços, software, hardware, fornecedores ou subcontratados usados por uma organização.
- Um ataque à cadeia de suprimentos (supply-chain attack) tem como alvo uma relação de confiança, em vez de atacar diretamente a organização final.

Exemplos:
- Atualização de software comprometida
- Biblioteca de terceiros vulnerável
- Comprometimento de conta de fornecedor
- Integração de API insegura
- Código malicioso inserido em um software
- Interrupção do provedor de nuvem

## Due Diligence de Fornecedores

- **Due Diligence:** Avaliar um fornecedor antes de usar o produto ou serviço.
- O objetivo é entender se o fornecedor consegue proteger adequadamente os dados e sistemas.

Itens comuns de avaliação:
- Questionário de segurança
- Relatório SOC 2
- Certificação ISO 27001
- Relatórios de PCI DSS, HIPAA ou outra conformidade, quando aplicável
- Práticas de manuseio de dados
- Métodos de criptografia
- Processo de controle de acesso
- Processo de resposta a incidentes
- Plano de continuidade de negócios e recuperação de desastres
- Processo de gestão de vulnerabilidades
- Lista de subcontratados

## Contratos e SLAs de Fornecedores

- **SLA (Service Level Agreement):** Acordo de Nível de Serviço que define o desempenho esperado do serviço.
- Os contratos devem explicar claramente as responsabilidades de segurança.

Itens importantes do contrato:
- Propriedade dos dados
- Prazo de notificação de violação (breach)
- Direitos de auditoria
- Requisitos de criptografia
- Expectativas de log e monitoramento
- Requisitos de disponibilidade
- RTO e RPO
- Direito de rescisão
- Retorno ou destruição segura dos dados

## Controle de Acesso para Fornecedores

- O acesso de fornecedores deve seguir o princípio do privilégio mínimo.
- O acesso deve ser temporário sempre que possível.
- As contas de fornecedores devem ser monitoradas e revisadas regularmente.

Boas práticas:
- Exigir MFA
- Usar contas nomeadas em vez de contas compartilhadas
- Restringir o acesso por horário, IP ou função
- Registrar (logar) a atividade do fornecedor
- Remover o acesso quando o trabalho for concluído
- Revisar o acesso privilegiado com frequência

## Monitoramento Contínuo

- A gestão de risco de fornecedores não é apenas uma avaliação única.
- Os fornecedores devem ser monitorados durante toda a relação.

O monitoramento pode incluir:
- Reavaliação anual
- Revisões de acesso
- Revisão de renovação de contrato
- Revisão de notificação de incidentes
- Revisão de relatórios de conformidade
- Monitoramento de notícias de segurança ou violações

## Offboarding de Fornecedores

- O offboarding é importante porque o acesso antigo de um fornecedor pode se tornar uma fragilidade de segurança.

Etapas do offboarding de fornecedores:
- Desativar contas
- Revogar chaves de API e tokens
- Remover VPN ou acesso remoto
- Recuperar ativos da empresa
- Confirmar a exclusão ou devolução dos dados
- Atualizar a documentação
- Revisar logs, se necessário

## Principais Conclusões

- Fornecedores terceirizados podem se tornar um caminho de ataque para dentro de uma organização.
- O acesso de fornecedores deve ser revisado, limitado, monitorado e removido quando não for mais necessário.
- Os contratos devem definir as expectativas de segurança antes que os problemas ocorram.
