# Automação e Orquestração

## Objetivos
- Entender os conceitos de automação e orquestração
- Explicar os casos de uso comuns de automação de segurança
- Identificar benefícios e riscos da resposta automatizada

## Sumário

1. [Automação](#automação)
2. [Orquestração](#orquestração)
3. [SOAR](#soar)
4. [Casos de Uso de Automação](#casos-de-uso-de-automação)
5. [Benefícios](#benefícios)
6. [Riscos](#riscos)
7. [Principais Conclusões](#principais-conclusões)

## Automação

- **Automação:** Uso de tecnologia para realizar tarefas repetíveis com trabalho manual mínimo.
- A automação é útil para tarefas comuns, previsíveis e bem definidas.

Exemplos:
- Analisar logs (parse)
- Gerar relatório
- Criar chamado (ticket)
- Executar varredura
- Enviar notificação

## Orquestração

- **Orquestração:** Coordenar múltiplas tarefas automatizadas entre ferramentas, sistemas e equipes.

Exemplo:
- Um alerta do SIEM dispara o enriquecimento.
- O IP é verificado em fontes de inteligência de ameaças.
- Um chamado (ticket) é criado.
- Um analista é notificado.
- Um bloqueio de firewall é preparado para aprovação.

## SOAR

- **SOAR (Security Orchestration, Automation, and Response):** Orquestração, Automação e Resposta de Segurança.
- As plataformas de SOAR conectam alertas, playbooks, ferramentas, aprovações e ações de resposta.

## Casos de Uso de Automação

Usos comuns de automação de segurança:
- Enriquecer endereços IP e domínios
- Desativar contas comprometidas
- Bloquear indicadores maliciosos
- Executar varreduras de vulnerabilidades
- Criar chamados de incidente
- Coletar evidências de endpoint
- Enviar notificações de incidente
- Gerar relatórios de conformidade
- Implantar patches

## Benefícios

- Resposta mais rápida
- Menos erros manuais
- Processo consistente
- Melhor coleta de evidências
- Redução da carga de trabalho do analista
- Relatórios mais fáceis

## Riscos

- Uma lógica incorreta pode causar ações erradas.
- Uma automação com permissões excessivas pode causar mais dano.
- Ações de alto impacto podem precisar de aprovação humana.
- As ações automatizadas devem ser registradas (logadas), testadas e revisadas.

## Principais Conclusões

- A automação é melhor para tarefas repetíveis.
- A orquestração conecta múltiplas ferramentas em um fluxo de trabalho.
- A resposta automatizada deve ser controlada e monitorada.
