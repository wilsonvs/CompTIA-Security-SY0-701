# Investigando um Incidente

## Objetivos
- Entender como investigar atividade suspeita usando evidências
- Identificar logs e artefatos úteis
- Construir uma linha do tempo e determinar o escopo

## Sumário

1. [Investigação](#investigação)
2. [Fontes de Evidência](#fontes-de-evidência)
3. [Linha do Tempo](#linha-do-tempo)
4. [Escopo](#escopo)
5. [Causa Raiz](#causa-raiz)
6. [Documentação](#documentação)
7. [Principais Conclusões](#principais-conclusões)

## Investigação

- **Investigação:** Processo de coletar e analisar evidências para entender o que aconteceu, como aconteceu, o que foi afetado e qual ação é necessária.
- As investigações devem se basear em evidências, não em suposições.

## Fontes de Evidência

Fontes comuns de evidência:
- Logs de autenticação
- Logs de endpoint
- Logs de firewall
- Logs de DNS
- Logs de VPN
- Logs de proxy
- Cabeçalhos de e-mail
- Logs de auditoria em nuvem
- Alertas de EDR
- Carimbos de data/hora de arquivos
- Logs de execução de processos

## Linha do Tempo

- **Linha do Tempo (Timeline):** Lista ordenada de eventos antes, durante e depois da atividade suspeita.

Campos da linha do tempo:
- Carimbo de data/hora
- Origem
- Usuário
- Host
- Endereço IP
- Evento
- Anotação do analista

Exemplo:
- 10:03 - Múltiplos logins falhos de IP externo
- 10:08 - Login bem-sucedido
- 10:12 - Nova regra de encaminhamento de caixa de e-mail criada

## Escopo

- **Escopo:** A extensão total de usuários, sistemas, dados e serviços afetados.

Perguntas de escopo:
- Um usuário é afetado ou vários?
- Um host é afetado ou vários?
- Dados sensíveis foram acessados?
- Houve tentativa de escalonamento de privilégio?
- O atacante ainda está ativo?
- Há alertas relacionados?

## Causa Raiz

- **Causa Raiz (Root Cause):** O principal motivo pelo qual o incidente aconteceu.

Exemplos:
- Credenciais roubadas
- Patch ausente
- Armazenamento em nuvem mal configurado
- E-mail de phishing
- Senha fraca
- Serviço de acesso remoto exposto

## Documentação

As anotações do incidente devem incluir:
- Resumo
- Linha do tempo
- Evidência
- Impacto
- Escopo
- Ações realizadas
- Recomendações
- Lições aprendidas

## Principais Conclusões

- Boas investigações identificam o que aconteceu, até onde se espalhou e o que precisa ser corrigido.
- As linhas do tempo tornam as evidências do incidente mais fáceis de entender.
