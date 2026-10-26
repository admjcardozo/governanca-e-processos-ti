# Catálogo de Indicadores de Desempenho — SGS/SGSI

## 1. Objetivo

Este documento apresenta um catálogo conceitual de indicadores para acompanhamento do Programa Integrado de Governança, Serviços e Segurança de TI (SGS/SGSI).

O objetivo é organizar indicadores que apoiem a avaliação do desempenho dos processos, dos níveis de serviço, dos riscos, dos controles e das iniciativas de melhoria contínua, contribuindo para a tomada de decisão e o alinhamento entre TI e negócio.

O catálogo estabelece uma estrutura de referência para definição, cálculo, interpretação e acompanhamento dos indicadores. Sua aplicação depende da validação das fórmulas, das fontes de dados, das responsabilidades e dos critérios de avaliação no contexto organizacional.

> **Natureza do projeto:** material autoral e conceitual para portfólio profissional. Os indicadores apresentados são propostas de referência. Não representam resultados reais, metas aprovadas ou evidências de desempenho de uma organização específica.

## 2. Princípios para definição de indicadores

| Princípio | Aplicação |
|---|---|
| Alinhamento estratégico | Relacionar o indicador a um objetivo, risco, serviço ou resultado relevante. |
| Definição inequívoca | Estabelecer o significado do indicador e o que será contabilizado. |
| Fórmula documentada | Definir numerador, denominador, unidade de medida e regras de cálculo, quando aplicáveis. |
| Fonte identificada | Especificar de onde virão os dados e como sua qualidade será verificada. |
| Periodicidade definida | Estabelecer a frequência de apuração e de análise. |
| Responsabilidade atribuída | Definir quem apura, valida, analisa e encaminha ações decorrentes. |
| Comparabilidade | Manter critérios consistentes ao comparar períodos, equipes ou serviços. |
| Rastreabilidade | Preservar dados de origem, critérios de cálculo e histórico de alterações. |
| Uso responsável | Evitar interpretações isoladas ou conclusões que os dados não sustentem. |

## 3. Estrutura mínima de um indicador

Cada indicador deverá possuir uma definição documentada. Recomenda-se utilizar os seguintes atributos:

| Atributo | Descrição |
|---|---|
| Identificador | Código único para facilitar referência e rastreabilidade. |
| Nome | Título claro e representativo do que está sendo medido. |
| Objetivo | Decisão, resultado ou aspecto de desempenho que o indicador pretende apoiar. |
| Definição | Descrição precisa do que será medido. |
| Fórmula | Regra de cálculo, incluindo numerador, denominador e critérios de inclusão, quando aplicáveis. |
| Unidade | Percentual, quantidade, tempo, valor monetário ou outra unidade pertinente. |
| Fonte de dados | Sistema, registro, relatório ou processo que fornece os dados. |
| Periodicidade | Frequência de apuração e de análise. |
| Responsável | Papel encarregado da apuração, validação ou análise. |
| Referência ou meta | Critério de comparação, quando formalmente definido. |
| Limitações | Restrições de interpretação, qualidade ou disponibilidade dos dados. |
| Ação decorrente | Encaminhamento esperado quando houver desvio ou oportunidade de melhoria. |

A meta, quando aplicável, deve ser definida e aprovada pelos responsáveis competentes. Não se deve atribuir uma meta fictícia a um indicador e apresentá-la como compromisso organizacional.

## 4. Catálogo de indicadores propostos

Os indicadores a seguir constituem uma seleção inicial de referência. A fórmula, a fonte e a periodicidade deverão ser validadas antes de qualquer utilização operacional.

### 4.1 Gestão de serviços e níveis de serviço

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-01 | Cumprimento de SLA | Chamados concluídos dentro do prazo acordado ÷ total de chamados concluídos sujeitos ao SLA × 100. | Avaliar o cumprimento dos compromissos de serviço. |
| IND-02 | Tempo médio de resolução | Soma dos tempos de resolução dos chamados elegíveis ÷ quantidade de chamados resolvidos. | Acompanhar o tempo necessário para resolver solicitações e incidentes. |
| IND-03 | Backlog de chamados | Quantidade de chamados abertos ao final do período, conforme critérios definidos. | Avaliar o volume de trabalho pendente. |
| IND-04 | Taxa de reabertura | Chamados reabertos no período ÷ total de chamados resolvidos no período × 100, conforme regra de contagem definida. | Identificar possíveis problemas de qualidade na resolução. |

**Cuidados de interpretação:** o cumprimento de SLA depende da qualidade dos registros de abertura, prioridade, pausa e encerramento. O tempo médio pode esconder casos extremos; por isso, poderá ser complementado por mediana, percentis ou segmentação por prioridade.

### 4.2 Incidentes, problemas e mudanças

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-05 | Incidentes recorrentes | Quantidade de incidentes classificados como recorrentes segundo critérios previamente definidos. | Identificar padrões que justificam investigação de problemas. |
| IND-06 | Tempo médio de resolução de problemas | Soma dos tempos de resolução dos problemas encerrados ÷ quantidade de problemas encerrados no período. | Acompanhar o tratamento estrutural de problemas. |
| IND-07 | Mudanças bem-sucedidas | Mudanças concluídas sem falha ou reversão atribuível, conforme critérios definidos ÷ total de mudanças concluídas × 100. | Avaliar a qualidade do processo de mudanças. |
| IND-08 | Taxa de mudanças emergenciais | Mudanças classificadas como emergenciais ÷ total de mudanças executadas no período × 100. | Acompanhar o uso do fluxo emergencial e identificar tendências. |

**Cuidados de interpretação:** mudanças emergenciais podem ser justificadas por situações legítimas. Uma taxa elevada deve motivar investigação de causas e contexto, não uma conclusão automática de falha de gestão.

### 4.3 Segurança da informação e continuidade

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-09 | Incidentes de segurança por severidade | Quantidade de incidentes registrados no período, segmentada por classificação de severidade. | Acompanhar o perfil dos incidentes de segurança. |
| IND-10 | Tempo de tratamento de incidentes de segurança | Tempo entre os marcos de início e encerramento definidos para cada incidente, analisado por período e severidade. | Avaliar a capacidade de resposta. |
| IND-11 | Ações de risco vencidas | Quantidade de ações de tratamento de riscos com prazo ultrapassado e sem encerramento válido. | Evidenciar pendências de tratamento. |
| IND-12 | Execução de testes de continuidade | Testes realizados conforme o planejamento aprovado ÷ testes previstos no período × 100. | Acompanhar a execução do programa de testes. |
| IND-13 | Ações pós-teste concluídas | Ações decorrentes de testes concluídas dentro do prazo ÷ total de ações com prazo vencido no período × 100, conforme critérios definidos. | Monitorar o tratamento das deficiências identificadas. |

**Cuidados de interpretação:** a quantidade de incidentes pode aumentar devido à melhoria na detecção e na notificação. Da mesma forma, a execução de um teste de continuidade não comprova, por si só, que os objetivos de recuperação foram atingidos.

### 4.4 Ativos, configuração e fornecedores

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-14 | Completude dos registros de ativos | Ativos elegíveis com os atributos obrigatórios preenchidos ÷ total de ativos elegíveis avaliados × 100. | Avaliar a qualidade do inventário. |
| IND-15 | Conformidade de configuração | Itens de configuração avaliados que atendem aos critérios definidos ÷ total de itens avaliados × 100. | Acompanhar a aderência a padrões de configuração. |
| IND-16 | Fornecedores avaliados | Fornecedores avaliados no período conforme critérios estabelecidos ÷ fornecedores previstos para avaliação no período × 100. | Acompanhar a execução do processo de avaliação de fornecedores. |
| IND-17 | Não conformidades de fornecedores em aberto | Quantidade de não conformidades registradas e ainda não encerradas conforme critérios definidos. | Acompanhar pendências que possam afetar serviços ou contratos. |

**Cuidados de interpretação:** o resultado depende da definição do universo avaliado, dos atributos obrigatórios, da amostragem e dos critérios de conformidade. A cobertura de avaliações não equivale, isoladamente, à qualidade do desempenho dos fornecedores.

### 4.5 Demanda, capacidade e custos

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-18 | Utilização de capacidade | Capacidade utilizada ÷ capacidade disponível, considerando a unidade e a janela de medição definidas. | Avaliar utilização de recursos e identificar restrições. |
| IND-19 | Desvio de custos de TI | Custo realizado menos custo de referência aprovado, apresentado em valor monetário e, quando pertinente, como percentual. | Acompanhar variações financeiras. |
| IND-20 | Variação da demanda | Demanda do período comparada à demanda de um período de referência, com critérios consistentes de contagem. | Identificar tendências e apoiar o planejamento de capacidade. |

**Cuidados de interpretação:** alta utilização de capacidade não é necessariamente positiva; pode indicar risco de saturação. Desvios financeiros exigem comparação com uma base válida, considerando escopo, período, câmbio, contratos e premissas aplicáveis.

### 4.6 Governança, controles e melhoria contínua

| ID | Indicador | Definição e cálculo de referência | Finalidade |
|---|---|---|---|
| IND-21 | Ações corretivas vencidas | Quantidade de ações corretivas com prazo ultrapassado e sem encerramento válido. | Acompanhar pendências de melhoria e correção. |
| IND-22 | Controles avaliados no período | Quantidade de controles avaliados conforme o plano e os critérios definidos. | Acompanhar a execução das avaliações planejadas. |
| IND-23 | Controles com resultado satisfatório | Controles avaliados que atenderam aos critérios definidos ÷ total de controles avaliados × 100. | Acompanhar os resultados das avaliações de controle. |
| IND-24 | Riscos com tratamento revisado | Riscos que tiveram o tratamento revisado conforme critérios de revisão ÷ total de riscos previstos para revisão no período × 100. | Acompanhar a atualização das avaliações de risco. |
| IND-25 | Melhorias concluídas | Quantidade de melhorias encerradas segundo critérios de conclusão definidos. | Acompanhar entregas de melhoria contínua. |

**Cuidados de interpretação:** um controle só deve ser classificado como satisfatório quando houver evidência suficiente para aplicar os critérios definidos. A quantidade de ações concluídas não demonstra, isoladamente, que os problemas foram resolvidos ou que os resultados esperados foram alcançados.

## 5. Modelo de ficha de indicador

A ficha abaixo pode ser utilizada como estrutura para formalizar cada indicador antes de incorporá-lo ao acompanhamento operacional.

| Campo | Preenchimento proposto |
|---|---|
| Identificador e nome | Código e título do indicador. |
| Objetivo associado | Objetivo, risco, processo ou serviço que será acompanhado. |
| Definição operacional | Evento, população e regras de inclusão e exclusão. |
| Fórmula validada | Cálculo documentado e testado. |
| Unidade de medida | Percentual, quantidade, tempo, valor monetário ou outra unidade. |
| Fonte e extração | Sistema de origem, consulta, relatório e procedimento de extração. |
| Periodicidade | Frequência de apuração e de análise. |
| Responsável pela apuração | Papel que prepara os dados. |
| Responsável pela validação | Papel que verifica consistência e confiabilidade. |
| Responsável pela decisão | Papel ou instância que avalia desvios e define encaminhamentos. |
| Meta ou limite | Critério aprovado, se aplicável. |
| Segmentações | Serviço, prioridade, categoria, unidade ou outra dimensão pertinente. |
| Limitações | Lacunas, riscos de viés e restrições de interpretação. |
| Ação esperada | Procedimento para análise, escalonamento ou melhoria. |

## 6. Governança do ciclo de vida dos indicadores

A gestão dos indicadores deve contemplar as etapas abaixo.

1. **Proposição:** identificar a necessidade de acompanhamento e o objetivo da medição.
2. **Definição:** estabelecer nome, conceito, fórmula, fonte, unidade e regras de cálculo.
3. **Validação:** confirmar a disponibilidade e a qualidade dos dados e testar o cálculo.
4. **Aprovação:** definir responsáveis, periodicidade e critérios de avaliação.
5. **Apuração:** coletar os dados e registrar a execução do cálculo.
6. **Análise:** interpretar resultados, tendências, variações e limitações.
7. **Encaminhamento:** definir ações quando houver desvios ou oportunidades relevantes.
8. **Revisão:** avaliar se o indicador continua útil, confiável e alinhado aos objetivos.
9. **Descontinuação controlada:** registrar a justificativa e preservar o histórico quando um indicador deixar de ser utilizado.

Mudanças na fórmula, na fonte, na população ou nos critérios de classificação devem ser documentadas, pois podem afetar a comparabilidade histórica.

## 7. Análise e comunicação de resultados

A análise de indicadores deve considerar mais do que o valor isolado de um período.

Sempre que pertinente, recomenda-se avaliar:

- tendência histórica;
- variação em relação à meta ou à referência aprovada;
- distribuição por prioridade, serviço ou categoria;
- impacto operacional e riscos associados;
- qualidade, completude e atualidade dos dados;
- causas prováveis dos desvios;
- ações em andamento e impedimentos;
- efeitos das ações já concluídas.

Um resultado fora da meta deve desencadear análise proporcional à sua relevância. Não se deve atribuir causalidade sem evidências suficientes, nem interpretar correlação como prova de causa e efeito.

## 8. Relação com a melhoria contínua

Os indicadores apoiam o ciclo de melhoria contínua ao fornecer informações para identificar desvios, avaliar causas, priorizar ações e acompanhar resultados.

A relação proposta é:

1. Medir o desempenho com critérios documentados.
2. Comparar os resultados com referências válidas.
3. Investigar desvios e oportunidades de melhoria.
4. Definir ações, responsáveis e prazos.
5. Acompanhar a execução.
6. Avaliar os resultados após a implementação.
7. Atualizar processos, controles ou indicadores quando necessário.

A medição deve apoiar decisões e aprendizagem organizacional, não apenas a produção de relatórios. Indicadores isolados também não devem ser utilizados como substitutos de avaliação contextual ou como mecanismo único de avaliação de pessoas.

## 9. Documentos relacionados

- [Documento Mestre SGS/SGSI](../docs/Documento_Mestre_SGS_SGSI_v1_1_revisado.docx)
- [Diagnóstico Executivo SGS/SGSI](../docs/Diagnostico_Executivo_SGS_SGSI_v1_2_revisado.docx)
- [Dicionário Corporativo de KPIs SGS/SGSI](../docs/Dicionario_Corporativo_KPIs_SGS_SGSI_v1_0.docx)
- [Registro Integrado de Riscos, Premissas e Dependências](../docs/Registro_Integrado_Riscos_Premissas_Dependencias_SGS_SGSI_v1_0.docx)
- [Glossário e Matriz RACI Integrados](../docs/Glossario_Matriz_RACI_Integrados_SGS_SGSI_v1_0.docx)
- [Catálogo de processos SGS/SGSI](../03-processos/README.md)
- [Governança, riscos e controles](../04-governanca-e-controles/README.md)
- [Roadmap de implantação e evolução](../02-roadmap/README.md)

Os documentos de referência devem ser consultados para validar as definições integradas e evitar divergências entre o catálogo de indicadores e os demais componentes do programa.

## 10. Limitações e condições de aplicação

Antes da utilização operacional dos indicadores, é necessário:

- validar os conceitos e as fórmulas;
- identificar e testar as fontes de dados;
- definir critérios de inclusão, exclusão e segmentação;
- atribuir responsabilidades de apuração, validação e análise;
- estabelecer metas e limites somente quando aprovados;
- verificar a qualidade e a comparabilidade dos dados;
- definir procedimentos de análise, escalonamento e ação;
- preservar os registros necessários à rastreabilidade.

Os indicadores deste documento são propostas conceituais. Não há, nesta síntese, comprovação de que as fórmulas tenham sido implantadas, de que os dados estejam disponíveis ou de que os resultados tenham sido medidos em uma organização real.

---

*Documento conceitual para portfólio profissional. Fórmulas, fontes, metas e critérios devem ser validados antes de eventual aplicação organizacional.*
