# Atividade Maliciosa

## Objetivos
- 2.4 - Dado um cenário, analisar indicadores de atividade maliciosa
- Identificar indicadores comuns de comprometimento
- Entender a triagem básica de alertas e a revisão de logs

## Sumário

1. [Atividade Maliciosa](#atividade-maliciosa)
2. [Indicadores de Comprometimento](#indicadores-de-comprometimento)
3. [Fontes Comuns de Log](#fontes-comuns-de-log)
4. [Atividade de Autenticação Suspeita](#atividade-de-autenticação-suspeita)
5. [Indicadores de Endpoint](#indicadores-de-endpoint)
6. [Indicadores de Rede](#indicadores-de-rede)
7. [Perguntas de Triagem](#perguntas-de-triagem)
8. [Principais Conclusões](#principais-conclusões)

## Atividade Maliciosa

- **Atividade Maliciosa:** Qualquer ação com o objetivo de roubar dados, obter acesso não autorizado, interromper sistemas, danificar arquivos ou evitar a detecção.
- A atividade maliciosa pode aparecer em logs, alertas, comportamento de endpoint, tráfego de rede, e-mail ou eventos de auditoria em nuvem.

## Indicadores de Comprometimento

- **IOC (Indicator of Compromise):** Evidência de que um sistema, conta, rede ou aplicação pode estar comprometido.

Exemplos:
- Hash de malware
- Endereço IP suspeito
- Domínio malicioso
- Processo desconhecido
- Tráfego de saída incomum
- Falhas repetidas de login
- Login bem-sucedido de local incomum
- Nova conta de administrador não autorizada
- Ferramentas de segurança desativadas
- Tarefa agendada suspeita

## Fontes Comuns de Log

- Logs de Segurança do Windows
- Logs de autenticação do Linux
- Logs de firewall
- Logs de DNS
- Logs de VPN
- Logs de proxy
- Alertas de EDR
- Logs de segurança de e-mail
- Logs de auditoria em nuvem
- Logs de servidor web

## Atividade de Autenticação Suspeita

Exemplos:
- Muitos logins falhos seguidos de um sucesso
- Login fora do horário normal de trabalho
- Login de país incomum
- Tentativas de MFA push fatigue (fadiga de aprovação por push)
- Tentativa de login em conta desativada
- Nova conta de administrador criada inesperadamente

## Indicadores de Endpoint

Exemplos:
- Processo desconhecido em execução
- Ferramenta de segurança desativada
- Comando suspeito no PowerShell
- Criptografia inesperada de arquivos
- Novo mecanismo de persistência
- Relação incomum entre processo pai e processo filho

## Indicadores de Rede

Exemplos:
- Conexão com IP malicioso conhecido
- Consultas DNS incomuns
- Grande transferência de dados de saída
- Padrão de beaconing (sinalização periódica)
- Tráfego para destino externo raro

## Perguntas de Triagem

- O que disparou o alerta?
- Qual usuário, host, IP ou processo está envolvido?
- A atividade é esperada?
- O que aconteceu antes e depois do evento?
- Há evidência de movimento lateral?
- É necessária contenção?

## Principais Conclusões

- A análise de atividade maliciosa exige evidências e contexto.
- Os logs ajudam a construir a linha do tempo, o escopo e o impacto.
