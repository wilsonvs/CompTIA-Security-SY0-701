# Alertas e Monitoramento

## Objetivos
- 4.4 - Explicar os conceitos e ferramentas de alerta e monitoramento de segurança
- Entender as fontes de log importantes
- Explicar a qualidade dos alertas, o ajuste (tuning) e a triagem

## Sumário

1. [Monitoramento](#monitoramento)
2. [Alertas](#alertas)
3. [Fontes de Log](#fontes-de-log)
4. [SIEM](#siem)
5. [Exemplos de Alertas](#exemplos-de-alertas)
6. [Ajuste de Alertas (Tuning)](#ajuste-de-alertas-tuning)
7. [Triagem](#triagem)
8. [Principais Conclusões](#principais-conclusões)

## Monitoramento

- **Monitoramento:** Coletar e revisar a atividade de sistemas, redes, aplicações, plataformas em nuvem e ferramentas de segurança.
- O monitoramento fornece visibilidade sobre o comportamento normal e anormal.

## Alertas

- **Alerta:** Uma notificação de que uma atividade específica pode exigir investigação.
- Os alertas podem vir do SIEM, EDR, IDS/IPS, firewalls, ferramentas de nuvem ou sistemas de segurança de e-mail.

Um bom alerta deve incluir:
- Nome do alerta
- Severidade
- Usuário
- Host
- Endereço IP
- Carimbo de data/hora (timestamp)
- Log de origem
- Motivo que o disparou
- Sugestão de etapas de triagem

## Fontes de Log

Fontes de log importantes:
- Logs de autenticação
- Logs de firewall
- Logs de DNS
- Logs de VPN
- Logs de proxy
- Logs de endpoint
- Logs de auditoria em nuvem
- Logs de segurança de e-mail
- Logs de servidor web

## SIEM

- **SIEM (Security Information and Event Management):** Gestão de Informações e Eventos de Segurança.
- Um SIEM coleta, armazena, pesquisa e correlaciona logs de múltiplas fontes.
- Ferramentas de SIEM ajudam os analistas a investigar a atividade entre sistemas.

## Exemplos de Alertas

- Múltiplos logins falhos
- Login bem-sucedido após falhas repetidas
- Viagem impossível (impossible travel)
- Detecção de malware
- Comando suspeito no PowerShell
- Nova conta de administrador
- Alteração em armazenamento em nuvem público
- Grande transferência de dados de saída

## Ajuste de Alertas (Tuning)

- **Tuning:** Ajustar a lógica do alerta para melhorar a precisão e reduzir o ruído.

O tuning pode incluir:
- Limiares (thresholds)
- Listas de permissão (allow lists)
- Janelas de supressão
- Criticidade do ativo
- Contexto do usuário
- Correlação com alertas relacionados

## Triagem

Perguntas básicas de triagem:
- O que disparou o alerta?
- Essa é uma atividade esperada?
- Quais usuário e sistema estão envolvidos?
- O que aconteceu antes e depois?
- É necessária contenção?

## Principais Conclusões

- O monitoramento fornece visibilidade.
- Os alertas transformam atividades importantes em trabalho de investigação.
- O tuning ajuda a reduzir falsos positivos e a fadiga do analista.
