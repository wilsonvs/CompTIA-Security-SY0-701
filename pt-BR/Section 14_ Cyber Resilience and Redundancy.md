# Resiliência Cibernética e Redundância

## Objetivos
- Entender como a resiliência dá suporte à disponibilidade
- Explicar redundância, backups e planejamento de recuperação
- Conhecer termos comuns de recuperação, como RTO e RPO

## Sumário

1. [Resiliência Cibernética](#resiliência-cibernética)
2. [Redundância](#redundância)
3. [Backups](#backups)
4. [Termos de Recuperação](#termos-de-recuperação)
5. [Tipos de Site](#tipos-de-site)
6. [Continuidade de Negócios e Recuperação de Desastres](#continuidade-de-negócios-e-recuperação-de-desastres)
7. [Testes e Validação](#testes-e-validação)
8. [Principais Conclusões](#principais-conclusões)

## Resiliência Cibernética

- **Resiliência Cibernética:** A capacidade de continuar operando, responder a interrupções, recuperar serviços e melhorar após um incidente.
- A resiliência está fortemente ligada à disponibilidade na tríade CIA.
- O objetivo é reduzir a indisponibilidade (downtime) e manter os serviços de negócio críticos em funcionamento.

## Redundância

- **Redundância:** Sistemas, componentes ou caminhos duplicados usados para evitar um ponto único de falha (single point of failure).

Exemplos:
- Múltiplas fontes de alimentação
- Nobreak (UPS) e gerador
- Armazenamento RAID
- Balanceador de carga (load balancer)
- Servidor de failover
- Múltiplos links de rede
- DNS secundário
- Banco de dados replicado
- Zonas de disponibilidade em nuvem

## Backups

- **Backup:** Uma cópia dos dados que pode ser restaurada após exclusão, corrupção, ransomware, falha de hardware ou desastre.

Boas práticas de backup:
- Criptografar os backups
- Proteger as credenciais de backup
- Monitorar as tarefas de backup
- Testar a restauração
- Manter cópias offline ou imutáveis sempre que possível
- Armazenar os backups separados dos sistemas de produção

Tipos de backup:
- **Backup Completo (Full):** Copia todos os dados selecionados.
- **Backup Incremental:** Copia as alterações desde o último backup.
- **Backup Diferencial:** Copia as alterações desde o último backup completo.

## Termos de Recuperação

- **RTO (Recovery Time Objective):** Objetivo de Tempo de Recuperação; quão rápido um serviço deve ser restaurado.
- **RPO (Recovery Point Objective):** Objetivo de Ponto de Recuperação; quanta perda de dados é aceitável.
- **MTD (Maximum Tolerable Downtime):** Tempo Máximo Tolerável de Indisponibilidade; maior interrupção aceitável.
- **MTTR (Mean Time To Repair):** Tempo Médio de Reparo.
- **MTBF (Mean Time Between Failures):** Tempo Médio Entre Falhas.

## Tipos de Site

- **Hot Site:** Site de recuperação totalmente pronto, com sistemas e dados disponíveis rapidamente.
- **Warm Site:** Site parcialmente pronto que precisa de alguma configuração.
- **Cold Site:** Instalação básica com pouco ou nenhum equipamento ativo.

## Continuidade de Negócios e Recuperação de Desastres

- **Continuidade de Negócios (Business Continuity):** Mantém as funções essenciais do negócio operando durante uma interrupção.
- **Recuperação de Desastres (Disaster Recovery):** Restaura os sistemas de tecnologia após uma interrupção.

Exemplo:
- A continuidade de negócios pode definir como a folha de pagamento continua.
- A recuperação de desastres pode definir como os servidores de folha de pagamento são restaurados.

## Testes e Validação

- Os planos devem ser testados antes de um incidente real.
- Testes de restauração de backup confirmam que a recuperação é realmente possível.
- Exercícios tabletop ajudam as equipes a praticar decisões e comunicação.

## Principais Conclusões

- A redundância ajuda a prevenir indisponibilidade.
- Os backups ajudam a recuperar após uma falha ou comprometimento.
- Os planos de recuperação devem ser testados, não apenas documentados.
