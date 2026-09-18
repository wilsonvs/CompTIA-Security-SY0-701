# Vulnerabilidades e Ataques

## Objetivos
- 2.3 - Explicar os diversos tipos de vulnerabilidades
- 2.4 - Dado um cenário, analisar indicadores de atividade maliciosa
- Entender os ataques comuns e os métodos de mitigação

## Sumário

1. [Vulnerabilidades](#vulnerabilidades)
2. [Superfície de Ataque](#superfície-de-ataque)
3. [Vulnerabilidades Comuns](#vulnerabilidades-comuns)
4. [Ataques Comuns](#ataques-comuns)
5. [Ataques a Aplicações Web](#ataques-a-aplicações-web)
6. [Ataques de Senha](#ataques-de-senha)
7. [Mitigações](#mitigações)
8. [Principais Conclusões](#principais-conclusões)

## Vulnerabilidades

- **Vulnerabilidade:** Uma fraqueza em software, hardware, configuração, processo ou design.
- As vulnerabilidades podem permitir acesso não autorizado, roubo de dados, interrupção de serviço, escalonamento de privilégio ou execução de malware.

## Superfície de Ataque

- **Superfície de Ataque (Attack Surface):** Todos os pontos possíveis pelos quais um atacante pode tentar entrar, interagir ou afetar um sistema.

Exemplos:
- Site público
- Página de login de VPN
- Caixa de entrada de e-mail
- Contas de usuário
- APIs
- Armazenamento em nuvem
- Rede sem fio
- Serviço de área de trabalho remota
- Integração com terceiros

## Vulnerabilidades Comuns

- Patches ausentes
- Senhas fracas
- Credenciais padrão
- Firewall mal configurado
- Armazenamento em nuvem público
- Permissões excessivas
- Dados sensíveis não criptografados
- APIs inseguras
- Validação de entrada deficiente
- Software sem suporte
- Portas e serviços abertos

## Ataques Comuns

- **Phishing:** Engana usuários para que revelem informações ou executem conteúdo malicioso.
- **Malware:** Software projetado para prejudicar sistemas ou roubar dados.
- **Ransomware:** Malware que criptografa arquivos e exige pagamento.
- **DoS/DDoS:** Ataque que interrompe a disponibilidade do serviço.
- **Escalonamento de Privilégio (Privilege Escalation):** Obter permissões maiores do que as originalmente atribuídas.
- **Man-in-the-Middle:** Interceptar ou alterar a comunicação entre duas partes.

## Ataques a Aplicações Web

- **SQL Injection:** Injetar comandos SQL em uma aplicação para acessar ou modificar dados do banco de dados.
- **XSS (Cross-Site Scripting):** Executar scripts maliciosos no navegador da vítima.
- **CSRF (Cross-Site Request Forgery):** Enganar o navegador de um usuário para que realize uma ação indesejada.
- **Directory Traversal:** Acessar arquivos fora do diretório pretendido.

## Ataques de Senha

- **Força Bruta (Brute Force):** Tentar muitas combinações de senha.
- **Password Spraying:** Tentar uma ou poucas senhas comuns em muitas contas.
- **Credential Stuffing:** Usar nomes de usuário e senhas vazados de outra violação (breach).
- **Ataque de Dicionário:** Tentar senhas de uma lista de palavras (wordlist).

## Mitigações

- Aplicar patches nos sistemas
- Exigir MFA
- Usar privilégio mínimo
- Validar a entrada de dados
- Segmentar as redes
- Criptografar dados sensíveis
- Monitorar os logs
- Desativar serviços não utilizados
- Aplicar baselines de configuração segura
- Treinar usuários para reconhecer phishing

## Principais Conclusões

- As vulnerabilidades criam oportunidades para ataques.
- Reduzir a superfície de ataque e aplicar controles em camadas diminui o risco.
