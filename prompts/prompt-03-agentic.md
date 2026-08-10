03 — O que torna um sistema Agentic?

Objetivo: Identificar, com base nas fontes selecionadas, quais características definem ou contribuem para o comportamento *agentic* de um sistema de Inteligência Artificial.

Prompt utilizado:
Com base exclusivamente nas cinco fontes deste notebook, explique o que define um sistema como agentic (agente). Identifique as características necessárias ou relevantes para esse comportamento, considerando raciocínio e ação, uso de ferramentas externas, interação com ambientes, planejamento, atualização de planos, tratamento de exceções, execução de tarefas e autonomia. Para cada característica, classifique a evidência como: (1) explicitamente sustentada pelas fontes, (2) parcialmente sustentada ou (3) não estabelecida. Não utilize conhecimento externo e não trate o ReAct como definição universal de agente.

Resultado:
A análise identificou os seguintes elementos associados ao comportamento *agentic*:

* **Raciocínio e ação:** integração entre *reasoning* e *acting*, especialmente demonstrada pelo framework ReAct;
* **Uso de ferramentas externas:** capacidade de interfacear com APIs, bases de conhecimento e outros recursos;
* **Interação com ambientes:** capacidade de obter informações e executar ações em ambientes externos;
* **Planejamento:** geração, acompanhamento e atualização de planos de ação;
* **Tratamento de exceções:** capacidade de modificar o curso de ação conforme novas informações;
* **Execução de tarefas:** avaliação do desempenho em tarefas computacionais reais e ambientes interativos;
* **Tarefas de múltiplas etapas:** combinação de diferentes ciclos de raciocínio e ação durante a resolução de problemas.

Classificação das evidências

| Característica              | Evidência                 |
| --------------------------- | ------------------------- |
| Raciocínio + ação           | Explicitamente sustentada |
| Uso de ferramentas externas | Explicitamente sustentada |
| Interação com ambientes     | Explicitamente sustentada |
| Planejamento                | Explicitamente sustentada |
| Tratamento de exceções      | Explicitamente sustentada |
| Tarefas de múltiplas etapas | Explicitamente sustentada |
| Autonomia absoluta          | Parcialmente sustentada   |
| Memória como requisito      | Não estabelecida          |

Cicatriz / Auditoria:

A análise inicial definiu a autonomia como uma característica central e apresentou o agente como um “executor autônomo”.
A auditoria identificou que essa formulação era mais forte do que as evidências disponíveis.
As fontes apresentam agentes executando tarefas de forma independente em determinados benchmarks, mas também discutem colaboração entre humanos e sistemas de IA. Portanto, **autonomia absoluta não deve ser tratada como requisito universal** com base apenas nessas fontes.
Também foi identificado que possuir memória não pode ser considerado uma característica definidora de agentes. A memória aparece, na realidade, como um dos problemas fundamentais ainda existentes nos modelos atuais.

Definição conservadora:
Com base exclusivamente nas fontes analisadas, um sistema *agentic* pode ser descrito como um sistema de IA capaz de **intercalar raciocínio e execução de ações**, permitindo que ele interaja com fontes ou ambientes externos, desenvolva e atualize planos e execute tarefas interativas.
Essa definição evita estabelecer que:

* todo agente precisa ser completamente autônomo;
* todo agente precisa possuir memória de longo prazo;
* o ReAct seja a única arquitetura ou método para agentes;
* agentes sejam necessariamente superiores a humanos em todas as tarefas.

Aprendizado

A principal conclusão desta etapa foi que **agenticidade deve ser analisada como um conjunto de capacidades observáveis**, e não apenas como um rótulo.
A interação com o ambiente, o uso de ferramentas, o planejamento e a capacidade de agir sobre informações recebidas são evidências mais concretas de comportamento *agentic* do que simplesmente a capacidade de gerar respostas sofisticadas.
