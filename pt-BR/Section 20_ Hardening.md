# Hardening

## Objetivos
- 4.1 - Dado um cenário, aplicar técnicas comuns de segurança a recursos computacionais
- Entender como o hardening reduz a superfície de ataque
- Identificar métodos de hardening para sistemas, redes, nuvem e aplicações

## Sumário

1. [Hardening](#hardening)
2. [Hardening de Sistema](#hardening-de-sistema)
3. [Hardening de Rede](#hardening-de-rede)
4. [Hardening de Nuvem](#hardening-de-nuvem)
5. [Hardening de Aplicação](#hardening-de-aplicação)
6. [Configuração Baseline](#configuração-baseline)
7. [Principais Conclusões](#principais-conclusões)

## Hardening

- **Hardening:** O processo de configurar sistemas com segurança e remover exposições desnecessárias.
- O hardening reduz o número de formas pelas quais um atacante pode comprometer um sistema.

Etapas comuns de hardening:
- Remover software não utilizado
- Desativar serviços não utilizados
- Aplicar patches
- Alterar senhas padrão
- Desativar contas padrão, quando possível
- Ativar o registro (logging)
- Exigir MFA
- Restringir o acesso de administrador
- Usar criptografia

## Hardening de Sistema

Exemplos:
- Aplicar patches nos sistemas operacionais
- Ativar a proteção de endpoint
- Configurar o firewall do host
- Exigir bloqueio de conta (account lockout)
- Desativar portas desnecessárias
- Restringir direitos de administrador local
- Ativar logs de auditoria

## Hardening de Rede

Exemplos:
- Revisar as regras de firewall
- Desativar portas de switch não utilizadas
- Usar protocolos de gerenciamento seguros
- Segmentar as redes
- Atualizar o firmware
- Proteger as configurações de rede sem fio
- Desativar protocolos inseguros

## Hardening de Nuvem

Exemplos:
- Usar IAM com privilégio mínimo
- Manter o armazenamento privado por padrão
- Restringir grupos de segurança
- Ativar logs de auditoria em nuvem
- Criptografar dados
- Rotacionar chaves de acesso
- Monitorar alterações de configuração

## Hardening de Aplicação

Exemplos:
- Validar a entrada de dados
- Proteger segredos (secrets)
- Usar cabeçalhos seguros (secure headers)
- Aplicar patches nas dependências
- Exigir autenticação e autorização
- Registrar eventos de segurança
- Evitar mensagens de erro detalhadas

## Configuração Baseline

- **Baseline:** Configuração mínima aprovada para um sistema.
- As baselines ajudam a manter os sistemas consistentes e seguros.

Exemplos:
- Baseline de servidor Windows
- Baseline de servidor Linux
- Baseline de firewall
- Baseline de IAM em nuvem
- Baseline de segurança de navegador

## Principais Conclusões

- O hardening é uma segurança preventiva.
- Baselines seguras ajudam a manter os sistemas consistentes, auditáveis e mais fáceis de manter.
