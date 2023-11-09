# Aula 04

**Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7964818/mod_resource/content/1/aula%205%202023.pdf) da aula.

* Artigo Referência da Aula: *Model Evaluation, Model Selection, and Algorithm Selection in Machine Learning*.

**Aula**

Nessa aula foram apresentados conceitos como seleção de modelo, seleção de algoritmo, teorema do não há almoço grátis, hiperparâmetros, subreajuste, trade-off entre viés e variância, divisão entre treino, validação e teste, método holdout, estratificação, viés pessimista, bootstrapping, leave-one-out e validação cruzada.

**Pergunta em aula: o pré-processamento é realizado tanto no treino quanto no teste?**

* O pré-processamento é feito em todos os dados, porém com a informação apenas do treino. Exemplo: padronização das variáveis apenas do treino.

* Aprende no treino, mas transforma tudo.

>Sugestão de 3 algoritmos de boosting para testar: XGBoost, LightGBM e CatBoost. Outros: RF e Rede Neural.

**Pergunta em aula sobre PyCaret.**

* Biblioteca que simplifica tarefas de ML. Ela automatiza etapas como pré-processamento de dados, treinamento de modelos e avaliação de desempenho.

* Auto ML / low code.

* Ela toma a decisão ao invés do "humano".
