# Ideia capturada — plataforma de acompanhamento premium do cliente

## Contexto
Mah está liderando implementações de IA na empresa e já criou um time interno de IA.

Ela quer ir além das iniciativas soltas e explorar a criação de um **web app** para centralizar tudo o que é relativo ao cliente e melhorar radicalmente a experiência dele.

## Problema percebido hoje
Atualmente não existe um controle claro sobre:
- frequência do cliente nas mentorias
- desempenho do cliente
- participação real
- evolução
- risco de churn
- sinais de que o cliente precisa de atenção

Existem 4 mentores envolvidos no acompanhamento:
- Felipe (principal)
- Marcelle
- Bárbara
- Day

O acompanhamento hoje tende a depender de percepção individual, memória e informações espalhadas.

## Papel principal da plataforma
A função central da plataforma seria:

**centralizar as informações dos clientes e permitir um acompanhamento premium da experiência deles.**

## Elementos já citados como importantes
- briefing de entrada do cliente
- centralização do contexto do cliente
- visão do engajamento e participação em mentorias
- acompanhamento de desempenho/evolução
- leitura de risco de churn
- apoio ao time para agir com mais consistência
- aproveitamento das gravações das mentorias como fonte adicional de contexto e insights

## Dados já disponíveis por mentorado
- briefing preenchido na entrada
- gravações de todas as mentorias, que podem servir para extrair contexto, evolução, dúvidas recorrentes e sinais de risco

## Eventos principais a registrar
- participação em mentoria individual
- participação em mentoria em grupo / plantão
- conquistas e marcos relevantes
- ausência recorrente ou sumiço das mentorias
- avaliação de desempenho/resultado dada pelos mentores

## Sinais de atenção / risco já mencionados
- cliente não aparece mais nas mentorias
- cliente não está desempenhando bem em relação aos resultados
- mentores podem atribuir notas de resultado como insumo para leitura de saúde

## Ideia atual de tela principal
- mentorados ativos
- próximos encontros da agenda dos mentores
- clientes em risco
- espaço para sugestões e priorização de ações

## Leitura estratégica inicial
Essa ideia se parece menos com “uma ferramenta com IA” e mais com um **hub operacional e relacional do cliente**.

O valor principal parece estar em:
- memória institucional do cliente
- continuidade entre mentores
- visibilidade da saúde do cliente
- ação proativa antes de problemas escalarem

## Hipótese inicial de proposta
Uma plataforma interna para centralizar briefing, histórico, participação, evolução, sinais de risco e próximos passos de cada cliente, permitindo que o time acompanhe a jornada com consistência, visão compartilhada e ação proativa.

## Regras e contexto operacional adicionais
- Todos os mentores podem ter contato com todos os mentorados
- Os agendamentos das mentorias são feitos via Google Meet
- Existem também plantões em grupo, nos quais pode haver mais de um mentorado ao mesmo tempo

## Implicações para o desenho da plataforma
- O relacionamento cliente ↔ mentor não é estritamente 1:1; precisa suportar acompanhamento compartilhado
- A plataforma deve lidar tanto com encontros individuais quanto com encontros em grupo
- Registros de presença, participação e histórico precisam considerar sessões com múltiplos mentorados
- Integrações ou referências de agenda/reunião provavelmente devem considerar o fluxo via Meet

## Possíveis módulos iniciais mencionados/derivados da conversa
- ficha do cliente
- briefing de entrada
- mentores vinculados
- histórico/timeline
- presença em mentorias
- observações qualitativas
- status de saúde do cliente
- risco de churn
- próximos passos

## MVP definido nesta etapa

### Objetivo do MVP
Permitir que o time:
- veja os mentorados ativos
- acompanhe os próximos encontros
- registre participação real
- identifique clientes em risco
- tenha um lugar único com briefing + contexto básico

### O que entra no MVP

#### 1. Cadastro do mentorado
- nome
- empresa
- data de entrada
- mentor principal
- outros mentores com contato
- briefing de entrada
- status: ativo / pausado / encerrado
- risco atual: baixo / médio / alto
- motivo do risco
- última participação

#### 2. Integração com Google Calendar
- puxar encontros da agenda
- mostrar título do evento
- data/hora
- link do Meet
- mentor responsável ou mentores
- tipo do encontro: individual / grupo

**Regra:** o Calendar organiza a agenda, mas não define presença automaticamente.

#### 3. Registro de participação
**Em encontro individual:**
- apareceu? sim / não
- observação rápida
- nota de engajamento
- nota de evolução

**Em encontro em grupo:**
- quais mentorados participaram
- observação rápida geral
- opcionalmente nota rápida por mentorado

#### 4. Sinalização de risco
- risco: baixo / médio / alto
- motivo
- próxima ação sugerida

#### 5. Registro de conquistas
- data
- mentorado
- conquista
- observação curta

### Tela principal do MVP
- mentorados ativos
- próximos encontros
- clientes em risco
- clientes sem participação recente
- conquistas recentes

### O que fica fora do MVP
- score automático complexo
- IA analisando tudo desde o dia 1
- painel analítico avançado
- automações de follow-up
- portal do cliente
- CRM completo
- transcrição automática obrigatória
- detecção automática de churn
- dezenas de tipos de evento
- dashboards muito sofisticados por mentor

### Regras operacionais mantidas
- todos os mentores podem ter contato com todos os mentorados
- encontros individuais e plantões em grupo precisam coexistir no modelo
- em grupo não existe convite por email para cada mentorado; o link é enviado no grupo e entra quem quiser
- a presença é marcada manualmente pelo mentor

## Próximo passo futuro
Retomar esta ideia depois para aprofundar:
- visão de produto
- telas do MVP
- backlog de funcionalidades
- papel futuro da IA na plataforma
- arquitetura/stack quando chegar a hora de construir

---

Captura feita para continuar a discussão depois, sem depender da memória da conversa.