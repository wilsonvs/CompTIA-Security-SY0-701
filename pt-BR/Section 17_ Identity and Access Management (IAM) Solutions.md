# Soluções de Gestão de Identidade e Acesso (IAM)

## Objetivos
- 4.6 - Dado um cenário, implementar a gestão de identidade e acesso
- Entender autenticação, autorização e auditoria (accounting)
- Comparar os modelos comuns de controle de acesso

## Sumário

1. [IAM](#iam)
2. [AAA](#aaa)
3. [Fatores de Autenticação](#fatores-de-autenticação)
4. [MFA](#mfa)
5. [Modelos de Controle de Acesso](#modelos-de-controle-de-acesso)
6. [Ciclo de Vida da Identidade](#ciclo-de-vida-da-identidade)
7. [Gestão de Acesso Privilegiado](#gestão-de-acesso-privilegiado)
8. [Principais Conclusões](#principais-conclusões)

## IAM

- **Gestão de Identidade e Acesso (IAM - Identity and Access Management):** Processos e tecnologias usados para gerenciar identidades e controlar o acesso a sistemas e dados.
- O IAM responde a duas perguntas principais:
  - Quem é você?
  - O que você tem permissão para acessar?

## AAA

- **Autenticação:** Verifica a identidade.
- **Autorização:** Determina o que a identidade pode acessar.
- **Auditoria (Accounting):** Registra a atividade para logs, auditorias e investigações.

Exemplo:
- Um usuário faz login com senha e MFA. Isso é autenticação.
- O usuário só pode acessar a pasta financeira. Isso é autorização.
- O sistema registra o acesso a arquivos. Isso é auditoria (accounting).

## Fatores de Autenticação

- **Algo que você sabe:** Senha ou PIN.
- **Algo que você tem:** Token, cartão inteligente, aplicativo autenticador.
- **Algo que você é:** Fator biométrico.
- **Onde você está:** Fator baseado em localização.
- **Algo que você faz:** Fator baseado em comportamento.

## MFA

- **MFA (Multi-Factor Authentication):** Autenticação Multifator; usa dois ou mais tipos de fatores diferentes.
- O MFA reduz o risco de comprometimento de conta caso uma senha seja roubada.

Exemplos:
- Senha + aplicativo autenticador
- Cartão inteligente + PIN
- Senha + biometria

## Modelos de Controle de Acesso

- **DAC (Discretionary Access Control):** Controle de Acesso Discricionário; o proprietário decide quem recebe acesso.
- **MAC (Mandatory Access Control):** Controle de Acesso Obrigatório; o acesso é baseado em rótulos e classificações.
- **RBAC (Role-Based Access Control):** Controle de Acesso Baseado em Função; o acesso é baseado no cargo/função.
- **ABAC (Attribute-Based Access Control):** Controle de Acesso Baseado em Atributos; o acesso é baseado em atributos como usuário, dispositivo, horário, localização ou risco.
- **Acesso Baseado em Regras (Rule-Based Access):** O acesso é controlado por regras definidas.

## Ciclo de Vida da Identidade

1. Criar a conta após aprovação.
2. Atribuir acesso com privilégio mínimo.
3. Revisar o acesso regularmente.
4. Modificar o acesso quando a função mudar.
5. Desativar ou remover o acesso durante o offboarding.

## Gestão de Acesso Privilegiado

- **PAM (Privileged Access Management):** Gestão de Acesso Privilegiado; controla e monitora contas de alto privilégio.
- Contas privilegiadas devem ter:
  - MFA
  - Registro (logging) robusto
  - Fluxo de aprovação
  - Gravação de sessão quando necessário
  - Acesso com tempo limitado

## Principais Conclusões

- O IAM é um dos controles de segurança mais importantes.
- Contas comprometidas são comuns em ataques reais, portanto a identidade deve ser protegida com cuidado.
