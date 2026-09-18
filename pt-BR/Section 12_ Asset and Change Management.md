# Gestão de Ativos e Mudanças

## Objetivos
- Entender por que o inventário de ativos é importante para a segurança
- Explicar a gestão do ciclo de vida de ativos
- Entender como a gestão de mudanças reduz o risco operacional e de segurança

## Sumário

1. [Gestão de Ativos](#gestão-de-ativos)
2. [Inventário de Ativos](#inventário-de-ativos)
3. [Classificação de Ativos](#classificação-de-ativos)
4. [Ciclo de Vida do Ativo](#ciclo-de-vida-do-ativo)
5. [Gestão de Mudanças](#gestão-de-mudanças)
6. [Registros de Mudança](#registros-de-mudança)
7. [Impacto de Segurança de uma Gestão de Mudanças Deficiente](#impacto-de-segurança-de-uma-gestão-de-mudanças-deficiente)
8. [Principais Conclusões](#principais-conclusões)

## Gestão de Ativos

- **Gestão de Ativos:** O processo de rastrear, proteger, manter e desativar os ativos organizacionais.
- Os ativos incluem hardware, software, dados, serviços em nuvem, contas, licenças, dispositivos de rede e processos de negócio.
- As equipes de segurança não conseguem proteger sistemas que não sabem que existem.

## Inventário de Ativos

- **Inventário de Ativos:** Uma lista de ativos e seus detalhes importantes.
- O inventário de ativos apoia a aplicação de patches, a gestão de vulnerabilidades, a resposta a incidentes, as auditorias e o planejamento de ciclo de vida.

Campos comuns de inventário:
- Nome do ativo
- ID do ativo
- Responsável (owner)
- Departamento
- Localização
- Endereço IP
- Nome do host (hostname)
- Sistema operacional
- Software instalado
- Função de negócio
- Criticidade
- Classificação de dados
- Status de aplicação de patches
- Status de garantia ou suporte

## Classificação de Ativos

- **Classificação:** Rotular os ativos com base em importância, sensibilidade ou impacto no negócio.
- A classificação ajuda a decidir quão fortemente um ativo deve ser protegido.

Exemplos:
- Público
- Interno
- Confidencial
- Restrito
- Crítico

Exemplo:
- Um site público e um banco de dados de folha de pagamento não devem ter o mesmo nível de controle de acesso, pois o banco de dados de folha de pagamento contém dados mais sensíveis.

## Ciclo de Vida do Ativo

Etapas do ciclo de vida do ativo:
1. **Aquisição (Procurement):** O ativo é comprado ou aprovado.
2. **Implantação (Deployment):** O ativo é configurado e colocado em operação.
3. **Manutenção:** O ativo recebe patches, é monitorado e tem suporte.
4. **Revisão:** A propriedade, o acesso e a configuração são verificados.
5. **Desativação (Decommissioning):** O ativo é removido do uso ativo.
6. **Descarte (Disposal):** O ativo é apagado com segurança, destruído, reciclado ou devolvido.

## Gestão de Mudanças

- **Gestão de Mudanças (Change Management):** Um processo formal para solicitar, revisar, aprovar, implementar e documentar mudanças.
- A gestão de mudanças reduz indisponibilidade, erros de configuração e mudanças não autorizadas.
- As mudanças podem incluir atualizações de software, alterações em regras de firewall, upgrades de sistema, alterações de configuração em nuvem e alterações de controle de acesso.

## Registros de Mudança

Um bom registro de mudança inclui:
- Descrição da mudança
- Motivo de negócio
- Sistemas afetados
- Risco e impacto
- Aprovação
- Etapas de implementação
- Plano de testes
- Plano de reversão (backout plan)
- Janela agendada
- Validação pós-mudança

## Impacto de Segurança de uma Gestão de Mudanças Deficiente

Uma gestão de mudanças deficiente pode causar:
- Interrupções (outages)
- Serviços expostos
- Registro (logging) quebrado
- Regras de firewall fracas
- Perda de dados
- Erros de privilégio
- Falhas de backup
- Configuração incorreta de ferramentas de segurança

## Principais Conclusões

- A gestão de ativos dá visibilidade sobre o que precisa ser protegido.
- A gestão de mudanças controla como os sistemas são modificados.
- Ambos os processos apoiam a segurança, a prontidão para auditoria e a resposta a incidentes.
