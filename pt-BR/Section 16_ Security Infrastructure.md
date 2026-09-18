# Infraestrutura de Segurança

## Objetivos
- Entender os componentes comuns de infraestrutura de segurança
- Explicar como as ferramentas dão suporte à prevenção, detecção e resposta
- Conhecer os controles comuns de rede, endpoint e monitoramento

## Sumário

1. [Infraestrutura de Segurança](#infraestrutura-de-segurança)
2. [Ferramentas de Segurança de Rede](#ferramentas-de-segurança-de-rede)
3. [Ferramentas de Segurança de Endpoint](#ferramentas-de-segurança-de-endpoint)
4. [Ferramentas de Monitoramento](#ferramentas-de-monitoramento)
5. [Ferramentas de Identidade e Acesso](#ferramentas-de-identidade-e-acesso)
6. [Ferramentas de Proteção de Dados](#ferramentas-de-proteção-de-dados)
7. [Principais Conclusões](#principais-conclusões)

## Infraestrutura de Segurança

- **Infraestrutura de Segurança:** As ferramentas, sistemas, plataformas e configurações usadas para proteger uma organização.
- Os controles de infraestrutura ajudam a prevenir ataques, detectar atividades suspeitas e apoiar a resposta a incidentes.

## Ferramentas de Segurança de Rede

- **Firewall:** Permite ou bloqueia o tráfego com base em regras.
- **IDS (Intrusion Detection System):** Sistema de Detecção de Intrusão; detecta tráfego suspeito e gera alertas.
- **IPS (Intrusion Prevention System):** Sistema de Prevenção de Intrusão; detecta e bloqueia tráfego suspeito.
- **VPN:** Cria acesso remoto criptografado.
- **Proxy:** Sistema intermediário que filtra ou monitora o tráfego web.
- **WAF (Web Application Firewall):** Firewall de Aplicação Web; protege aplicações web contra ataques web comuns.
- **NAC (Network Access Control):** Controle de Acesso à Rede; controla quais dispositivos podem se conectar à rede.

## Ferramentas de Segurança de Endpoint

- **Antivírus:** Detecta e remove malware conhecido.
- **EDR (Endpoint Detection and Response):** Detecção e Resposta de Endpoint; monitora o comportamento do endpoint e apoia investigações.
- **Firewall de Host:** Controla o tráfego em um único sistema.
- **Criptografia de Disco:** Protege os dados caso um dispositivo seja perdido ou roubado.
- **Controle de Aplicações:** Permite que apenas aplicações aprovadas sejam executadas.

## Ferramentas de Monitoramento

- **SIEM:** Coleta, pesquisa e correlaciona logs para monitoramento de segurança.
- **SOAR:** Automatiza e orquestra os fluxos de trabalho de resposta.
- **Servidor Syslog:** Coleta logs de sistemas e dispositivos de rede.
- **Captura de Pacotes (Packet Capture):** Registra o tráfego de rede para análise.

## Ferramentas de Identidade e Acesso

- Serviços de diretório
- Sistemas de MFA
- Single sign-on (SSO)
- Gestão de acesso privilegiado
- Ferramentas de governança de identidade

## Ferramentas de Proteção de Dados

- **DLP (Data Loss Prevention):** Prevenção de Perda de Dados; ajuda a impedir a movimentação não autorizada de dados sensíveis.
- Plataformas de criptografia
- Sistemas de backup
- Sistemas de gestão de chaves
- Ferramentas de gestão de direitos (rights management)

## Principais Conclusões

- As ferramentas de infraestrutura devem funcionar em conjunto.
- Um firewall sozinho não é suficiente; a segurança precisa de controles de endpoint, identidade, registro (logging) e proteção de dados.
