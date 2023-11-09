# Aula 04

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7964818/mod_resource/content/1/aula%205%202023.pdf) utilizados na aula.

* [Artigo](https://arxiv.org/abs/1811.12808) referência da aula: *Model Evaluation, Model Selection, and Algorithm Selection in Machine Learning*.

### **Aula**

Na aula foram apresentados conceitos como seleção de modelo, seleção de algoritmo, teorema do não há almoço grátis, hiperparâmetros, subreajuste, trade-off entre viés e variância, divisão entre treino, validação e teste, método holdout, estratificação, viés pessimista, bootstrapping, leave-one-out e validação cruzada.

**Pergunta em aula: o pré-processamento é realizado tanto no treino quanto no teste?**

* O pré-processamento é feito em todos os dados, porém com a informação apenas do treino. Exemplo: padronização das variáveis apenas do treino.

* Aprende no treino, mas transforma tudo.

>Sugestão de 3 algoritmos de boosting para testar: XGBoost, LightGBM e CatBoost. Outros: RF e Rede Neural.

**Pergunta em aula sobre PyCaret.**

* Biblioteca que simplifica tarefas de ML. Ela automatiza etapas como pré-processamento de dados, treinamento de modelos e avaliação de desempenho.

* Auto ML / low code.

* Ela toma a decisão ao invés do "humano".

### **Artigo**

* Técnicas de avaliação do modelo.

* Acurácia: predições corretas/casos. O quanto o algoritmo acerta. Na saúde, os problemas de sáude são raros (a maioria), por isso não é muito utilizada. Exemplo, quem vai a óbito no próximo ano, a proporção é muito pequena.

* Viés: erro consiste do algoritmo.

* Objetivo de ML (`Y = f(x)`): predizer Y (variável de interesse) por meio de um conjunto de regras por meio de uma função das minhas variáveis preditoras.

* Hiperparâmetros: parâmetros de ajuste de um algoritmo de ML. Exemplo, valor que definie a profundidade máxima de uma árvore de decisão. Tem que ser decidido por nós humanos. Tentativas de diminuir a complexidade do modelo.

* Parâmetros: que o algoritmo ajusta aos dados de treino. O que ele aprende. Exemplo, beta zero da regressão linear.

* Holdout: técnica de avalição de qualidade do algoritmo. A estimativa da performace é dada pelos acertos.

* Viés vs variância. High Variance (overfit/sobreajuste) = decorou os dados. High bias (underfit). "Just rigth".

* Quanto mais dados diminui a acurácia no treino e aumenta no teste (tendência).

* Bootstrapping: reamostragem com reposição. Exemplo, RF faz isso (dados sintéticos).

* Validação: "mini teste" (teste dentro do treino) para decidir o melhor hiperparâmetro.

* Validação cruzada: todos os dados de treino virão treino e validação. 5-fold, divide o treino em cinco partes iguais (4 vira treino e 1 validação) e tenho 5 medidas de performace. O mais usual é 10-fold.

