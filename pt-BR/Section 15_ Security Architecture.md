# Arquitetura de Segurança

## Objetivos
- 3.1 - Comparar e contrastar as implicações de segurança de diferentes modelos de arquitetura
- Entender os princípios de design seguro
- Explicar segmentação, zero trust, defesa em profundidade (defense in depth) e privilégio mínimo

## Sumário

1. [Arquitetura de Segurança](#arquitetura-de-segurança)
2. [Defesa em Profundidade](#defesa-em-profundidade)
3. [Zero Trust](#zero-trust)
4. [Segmentação](#segmentação)
5. [Privilégio Mínimo](#privilégio-mínimo)
6. [Arquitetura em Nuvem](#arquitetura-em-nuvem)
7. [Arquitetura de Aplicações](#arquitetura-de-aplicações)
8. [Principais Conclusões](#principais-conclusões)

## Arquitetura de Segurança

- **Arquitetura de Segurança:** O design de sistemas, redes, aplicações, recursos em nuvem e controles para proteger a confidencialidade, integridade e disponibilidade.
- Uma boa arquitetura reduz os caminhos de ataque e limita o dano quando um controle falha.

## Defesa em Profundidade

- **Defesa em Profundidade (Defense in Depth):** Uso de múltiplas camadas de controles de segurança.
- Se um controle falhar, outro controle ainda pode reduzir o ataque.

Exemplos:
- Firewall
- MFA
- Proteção de endpoint
- Segmentação de rede
- Registro e monitoramento (logging e monitoring)
- Backups
- Conscientização de segurança

## Zero Trust

- **Zero Trust:** Modelo de segurança baseado em nunca confiar por padrão e sempre verificar.
- O zero trust assume que ameaças podem existir tanto dentro quanto fora da rede.

Ideias do zero trust:
- Verificar identidade
- Usar privilégio mínimo
- Verificar a integridade do dispositivo
- Monitorar a atividade
- Segmentar o acesso
- Avaliar o risco continuamente

## Segmentação

- **Segmentação:** Dividir redes ou sistemas em áreas menores e isoladas.
- A segmentação ajuda a reduzir o movimento lateral.

Exemplos:
- Separar o Wi-Fi de convidados da rede interna
- Separar servidores das estações de trabalho dos usuários
- Separar sistemas de pagamento dos sistemas gerais
- Usar VLANs, firewalls e listas de controle de acesso (ACLs)

## Privilégio Mínimo

- **Privilégio Mínimo (Least Privilege):** Usuários e sistemas devem ter apenas o acesso necessário para realizar as tarefas exigidas.
- Reduz o impacto caso uma conta ou sistema seja comprometido.

## Arquitetura em Nuvem

A arquitetura em nuvem deve considerar:
- Modelo de responsabilidade compartilhada
- Funções (roles) e permissões de IAM
- Grupos de segurança
- Criptografia
- Registro (logging)
- Gestão de chaves
- Backup
- Exposição pública

## Arquitetura de Aplicações

Aplicações seguras devem incluir:
- Autenticação
- Autorização
- Validação de entrada (input validation)
- Gestão segura de sessão
- APIs seguras
- Tratamento de erros
- Registro (logging)
- Gestão de segredos (secrets management)

## Principais Conclusões

- A arquitetura de segurança é o design seguro feito antes que os problemas aconteçam.
- Um bom design usa camadas, privilégio mínimo, segmentação e monitoramento.
