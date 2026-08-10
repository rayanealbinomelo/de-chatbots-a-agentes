05 — Auditoria Causal

Objetivo: Verificar se as explicações apresentadas para o fenômeno da *jagged frontier* são realmente sustentadas pelas fontes ou se representam inferências produzidas a partir das informações disponíveis.

Prompt utilizado: Audite as explicações causais apresentadas na análise anterior sobre a “jagged frontier”. Para cada explicação, determine se ela é: (1) evidência direta das fontes, (2) inferência plausível ou (3) afirmação não sustentada. Analise especificamente as relações entre desempenho em benchmarks, memorização, grounding simbólico, causalidade, memória, embodiment e fragilidade cognitiva. Verifique também se é possível afirmar que essas limitações explicam diretamente falhas específicas dos modelos, como erros em tarefas simples de percepção. Não utilize conhecimento externo. Ao final, apresente uma tabela classificando cada relação causal e explique as limitações da evidência.

Resultado da auditoria: A análise identificou diferentes níveis de sustentação para as explicações apresentadas.

| Explicação                                            | Classificação        | Justificativa                                                                                            |
| ----------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------------------- |
| Fragilidade cognitiva dos LLMs                        | Evidência direta     | As fontes descrevem as capacidades cognitivas como superficiais e frágeis.                               |
| Falta de *symbol grounding*                           | Evidência direta     | É apresentada como um dos problemas fundamentais relacionados à inteligência geral.                      |
| Limitações de causalidade                             | Evidência direta     | A causalidade é identificada como um dos desafios fundamentais.                                          |
| Limitações de memória                                 | Evidência direta     | A memória aparece como um dos problemas fundamentais dos modelos atuais.                                 |
| Falta de *embodiment*                                 | Evidência direta     | A corporificação é apresentada como um princípio necessário para uma inteligência fisicamente plausível. |
| Memorização como causa do desempenho                  | Inferência plausível | As fontes não afirmam diretamente que o sucesso nos benchmarks seja causado por memorização.             |
| Falta de *grounding* como causa de um erro específico | Inferência           | As fontes apresentam o problema de forma geral, mas não atribuem diretamente uma falha específica a ele. |

Principal correção
A auditoria mostrou que não é suficiente identificar uma limitação existente nos modelos e, em seguida, afirmar que ela é a causa direta de determinado erro.
Por exemplo:
**A fonte afirma:** os modelos apresentam problemas relacionados a *symbol grounding*.
Isso não permite concluir automaticamente:
 **“O modelo errou ao interpretar um relógio porque não possui symbol grounding.”**
A segunda afirmação estabelece uma relação causal específica que as fontes não demonstram.

Memorização versus compreensão:

A hipótese de que modelos apresentam alto desempenho em determinados benchmarks devido à memorização foi classificada como **inferência plausível**.
Embora as fontes descrevam modelos treinados em grandes volumes de dados e caracterizem algumas capacidades como superficiais e frágeis, elas não estabelecem diretamente que os resultados observados sejam consequência de memorização em vez de compreensão.
Por isso, essa hipótese não deve ser apresentada como fato.

Limitação metodológica
A principal limitação identificada foi a diferença entre:
**correlação ou coexistência de fenômenos**
e
**relação causal comprovada.**

As fontes fornecem evidências sobre:

* desempenho em benchmarks;
* limitações cognitivas;
* problemas de grounding;
* causalidade;
* memória;
* embodiment.

Porém, elas não necessariamente estabelecem uma cadeia causal direta entre cada limitação teórica e cada falha observada.

Aprendizado
A auditoria causal demonstrou a importância de separar três níveis de afirmação:

1. Evidência direta
A fonte afirma explicitamente determinada informação.

2. Inferência plausível
A informação pode ser deduzida razoavelmente a partir das fontes, mas não foi afirmada diretamente.

3. Afirmação não sustentada
A conclusão ultrapassa o que as fontes permitem afirmar.

Essa distinção reduz o risco de transformar interpretações da IA em fatos científicos.

Conclusão: A auditoria mostrou que o uso crítico de IA não termina quando uma resposta parece convincente.

É necessário verificar:

**o que a fonte realmente afirma → o que pode ser inferido → o que não pode ser concluído.**

Essa etapa tornou-se uma das principais “cicatrizes” do projeto e demonstra a aplicação de pensamento crítico à utilização de ferramentas de IA.
