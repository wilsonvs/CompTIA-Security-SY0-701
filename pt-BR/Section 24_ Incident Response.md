# Resposta a Incidentes

## Objetivos
- 4.8 - Explicar as atividades apropriadas de resposta a incidentes
- Entender o ciclo de vida da resposta a incidentes
- Conhecer as ações comuns de contenção, erradicação e recuperação

## Sumário

1. [Resposta a Incidentes](#resposta-a-incidentes)
2. [Preparação](#preparação)
3. [Detecção e Análise](#detecção-e-análise)
4. [Contenção](#contenção)
5. [Erradicação](#erradicação)
6. [Recuperação](#recuperação)
7. [Lições Aprendidas](#lições-aprendidas)
8. [Principais Conclusões](#principais-conclusões)

## Resposta a Incidentes

- **Resposta a Incidentes:** Processo de se preparar, detectar, analisar, conter, erradicar, recuperar-se e aprender com incidentes de segurança.
- Um processo estruturado reduz a confusão durante eventos de alta pressão.

## Preparação

A preparação inclui:
- Playbooks
- Listas de contatos
- Registro (logging)
- Ferramentas
- Permissões de acesso
- Backups
- Treinamento
- Exercícios tabletop

## Detecção e Análise

- Determinar se um alerta é um incidente real.
- Identificar usuários, sistemas, IPs, arquivos e dados afetados.
- Construir uma linha do tempo inicial.

Perguntas:
- O que aconteceu?
- Quando aconteceu?
- Quais ativos são afetados?
- A ameaça ainda está ativa?
- Quais evidências sustentam a conclusão?

## Contenção

- **Contenção:** Limitar o dano e impedir a propagação.

Exemplos:
- Desativar conta
- Isolar endpoint
- Bloquear IP ou domínio
- Remover o sistema da rede
- Desativar chave de API comprometida

## Erradicação

- **Erradicação:** Remover a causa do incidente.

Exemplos:
- Remover o malware
- Aplicar patch na vulnerabilidade explorada
- Excluir o mecanismo de persistência
- Reconstruir o sistema comprometido
- Remover a conta não autorizada

## Recuperação

- **Recuperação:** Restaurar os sistemas ao funcionamento normal.

Exemplos:
- Restaurar a partir do backup
- Reconectar os sistemas limpos
- Redefinir as credenciais
- Monitorar a recorrência
- Validar a operação dos serviços de negócio

## Lições Aprendidas

- Revisar o que aconteceu após o incidente.
- Identificar a causa raiz, a linha do tempo, o impacto, as ações de resposta e as melhorias.

## Principais Conclusões

- A resposta a incidentes controla o dano e restaura as operações.
- A documentação e as evidências são importantes durante todo o processo.
