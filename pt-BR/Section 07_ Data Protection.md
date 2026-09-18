# Proteção de Dados

## Objetivos
- Entender os conceitos de proteção de dados
- Explicar classificação, retenção e prevenção de perda de dados
- Identificar controles usados para proteger dados em repouso, em trânsito e em uso

## Sumário

1. [Proteção de Dados](#proteção-de-dados)
2. [Estados dos Dados](#estados-dos-dados)
3. [Classificação de Dados](#classificação-de-dados)
4. [Manuseio de Dados](#manuseio-de-dados)
5. [Prevenção de Perda de Dados](#prevenção-de-perda-de-dados)
6. [Criptografia e Mascaramento](#criptografia-e-mascaramento)
7. [Retenção e Descarte](#retenção-e-descarte)
8. [Dados de Privacidade](#dados-de-privacidade)
9. [Principais Conclusões](#principais-conclusões)

## Proteção de Dados

- **Proteção de Dados:** Controles e processos usados para manter os dados confidenciais, precisos, disponíveis e devidamente manuseados.
- A proteção de dados se aplica a arquivos, bancos de dados, e-mails, backups, armazenamento em nuvem, logs e documentos impressos.

## Estados dos Dados

- **Dados em Repouso (Data at Rest):** Dados armazenados em disco, banco de dados, backup ou armazenamento em nuvem.
  - Exemplo: arquivo armazenado em um servidor.

- **Dados em Trânsito (Data in Transit):** Dados se movendo pela rede.
  - Exemplo: tráfego web via HTTPS.

- **Dados em Uso (Data in Use):** Dados sendo ativamente processados por um sistema ou usuário.
  - Exemplo: documento aberto na memória.

## Classificação de Dados

- **Classificação de Dados:** Rotular os dados com base na sensibilidade e na proteção exigida.

Exemplos:
- Público
- Interno
- Confidencial
- Restrito

A classificação ajuda a determinar:
- Quem pode acessar os dados
- Como os dados devem ser armazenados
- Como os dados devem ser transmitidos
- Como os dados devem ser descartados

## Manuseio de Dados

Regras de manuseio de dados podem incluir:
- Armazenar dados sensíveis apenas em locais aprovados
- Criptografar arquivos sensíveis
- Restringir o acesso por função (role)
- Não compartilhar dados confidenciais por e-mail pessoal
- Usar serviços de nuvem aprovados
- Seguir os requisitos de retenção

## Prevenção de Perda de Dados

- **DLP (Data Loss Prevention):** Tecnologia de prevenção de perda de dados usada para detectar ou impedir a movimentação não autorizada de dados.

O DLP pode monitorar:
- E-mail
- Atividade de cópia em endpoints
- Uploads para a nuvem
- Tráfego web
- Mídia removível

Exemplo:
- O DLP bloqueia um usuário de enviar por e-mail uma planilha contendo números de cartão de crédito para fora da empresa.

## Criptografia e Mascaramento

- **Criptografia:** Converte dados legíveis em uma forma ilegível sem a chave correta.
- **Mascaramento:** Oculta parte dos dados mantendo-os utilizáveis.
- **Tokenização:** Substitui dados sensíveis por um token não sensível.

Exemplos:
- Criptografar o disco rígido do notebook
- Mascarar o número do cartão de crédito, exceto os últimos quatro dígitos
- Tokenizar dados de cartão de pagamento

## Retenção e Descarte

- **Retenção:** Define por quanto tempo os dados devem ser mantidos.
- **Descarte:** Remoção segura dos dados quando não são mais necessários.

Métodos de descarte:
- Trituração (shredding)
- Limpeza (wiping)
- Desmagnetização (degaussing)
- Destruição física
- Processo seguro de exclusão em nuvem

## Dados de Privacidade

- **PII:** Informação Pessoalmente Identificável (Personally Identifiable Information).
- **PHI:** Informação de Saúde Protegida (Protected Health Information).
- **SPII:** Informação Pessoalmente Identificável Sensível (Sensitive Personally Identifiable Information).

Exemplos:
- Nome, endereço, número de telefone
- Número de Seguro Social (ou equivalente, como CPF)
- Prontuários médicos
- Informações de contas financeiras

## Principais Conclusões

- Os dados devem ser protegidos com base na sensibilidade e no valor para o negócio.
- Classificação, criptografia, DLP, retenção e descarte seguro contribuem para a proteção de dados.
