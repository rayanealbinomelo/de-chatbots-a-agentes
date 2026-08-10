De Chatbots a Agentes: para onde está indo a Inteligência Artificial?

Um estudo sobre a evolução da Inteligência Artificial, dos modelos conversacionais aos sistemas agentes.

Sobre o projeto:
Este projeto foi desenvolvido como um **caderno temático de estudos utilizando o NotebookLM** para investigar a evolução recente da Inteligência Artificial e compreender como os sistemas de IA passaram de modelos predominantemente conversacionais para sistemas capazes de raciocinar, utilizar ferramentas e executar ações em ambientes externos.

A pesquisa também busca compreender as limitações atuais desses sistemas e os desafios envolvidos no desenvolvimento de uma IA mais geral, confiável e capaz de atuar em diferentes contextos.

Objetivos:
* Compreender os principais marcos da evolução recente da IA;
* Investigar as diferenças entre chatbots, assistentes e agentes;
* Identificar características associadas a sistemas *agentic*;
* Analisar as capacidades e limitações dos modelos atuais;
* Compreender o conceito de *jagged frontier*;
* Investigar tendências relacionadas ao futuro da Inteligência Artificial;
* Praticar engenharia de prompts;
* Desenvolver uma abordagem crítica para analisar respostas produzidas por IA;
* Diferenciar evidências, inferências, projeções e especulações.

Curadoria de fontes:

Foram selecionadas cinco fontes abertas para compor o caderno temático no NotebookLM:
1. **Attention Is All You Need — Vaswani et al. (2017)**
   Artigo que apresenta a arquitetura Transformer e o mecanismo de atenção.
   [Acessar no arXiv](https://arxiv.org/abs/1706.03762)

2. **ReAct: Synergizing Reasoning and Acting in Language Models — Yao et al. (2022)**
   Estudo sobre a integração entre raciocínio e ação em modelos de linguagem.
   [Acessar no arXiv](https://arxiv.org/abs/2210.03629)

3. **DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning (2025)**
   Fonte utilizada para analisar avanços recentes em modelos de raciocínio e capacidades de fronteira.
   [Acessar no arXiv](https://arxiv.org/abs/2501.03151)

4. **AI Index Report 2026 — Stanford HAI**
   Relatório utilizado para analisar a evolução das capacidades, adoção, agentes, segurança e impactos da IA.
   [Acessar o AI Index 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report)

5. **The Future of Jobs Report 2025 — World Economic Forum**
   Fonte utilizada para analisar transformações no mercado de trabalho, habilidades e necessidades de *reskilling* relacionadas à IA.
   [Acessar o relatório](https://www.weforum.org/publications/the-future-of-jobs-report-2025/digest/)

Metodologia
A pesquisa foi conduzida de forma **iterativa** no NotebookLM.
O processo seguiu o seguinte fluxo:

Fontes
  ↓
Pergunta / Prompt
  ↓
Resposta da IA
  ↓
Auditoria
  ↓
Identificação de limitações
  ↓
Refinamento
  ↓
Síntese final

As respostas foram analisadas buscando diferenciar:

* **Evidência direta** — informação explicitamente sustentada pelas fontes;
* **Inferência** — conclusão derivada das informações disponíveis;
* **Projeção** — expectativa apresentada pelas próprias fontes;
* **Especulação** — afirmação que não pode ser sustentada pelo material analisado.

Essa abordagem foi utilizada para evitar que interpretações produzidas pela IA fossem apresentadas automaticamente como fatos.

Estrutura do projeto

├── fontes/
│   └── Fontes utilizadas na pesquisa
│
├── prompts/
│   ├── prompt-01-mapeamento.md
│   ├── prompt-02-chatbot-assistente-agente.md
│   ├── prompt-03-agentic.md
│   ├── prompt-04-jagged-frontier.md
│   ├── prompt-05-auditoria-causal.md
│   └── prompt-06-tendencias-futuro.md
│
└── miniguia/
    └── README.md

fontes/
Reúne as fontes utilizadas como base para a investigação no NotebookLM.

prompts/
Documenta as perguntas utilizadas durante a pesquisa, incluindo respostas, auditorias, correções e as principais **“cicatrizes”** encontradas durante o processo.

miniguia/
Apresenta a síntese final do estudo, reunindo:

* resumo estruturado;
* glossário;
* cicatrizes e aprendizados;
* prompts reutilizáveis.

Por que documentar as “cicatrizes”?

Uma parte importante do projeto foi perceber que uma resposta de IA pode ser **convincente sem ser completamente sustentada pelas fontes**.

Durante a investigação, algumas interpretações foram posteriormente classificadas como:

* simplificações;
* inferências plausíveis;
* generalizações;
* relações causais não comprovadas.

Esses casos foram registrados e corrigidos, tornando o processo de auditoria parte da própria entrega.

Principal aprendizado
O objetivo deste projeto não foi apenas descobrir **o que a IA consegue fazer**, mas também compreender **como avaliar criticamente aquilo que uma IA afirma**.

A principal metodologia aprendida pode ser resumida em:

**Investigar → Questionar → Auditar → Corrigir → Consolidar**

Entrega final

**[Acessar o Miniguia de Estudo](miniguia/README.md)**

**[Ver os prompts e o processo de investigação](prompts/)**


Tema central

**De Chatbots a Agentes: para onde está indo a Inteligência Artificial?**

A pergunta central que orientou o projeto foi:
**O que muda quando uma IA deixa de apenas responder e passa a raciocinar, utilizar ferramentas e executar ações?**
