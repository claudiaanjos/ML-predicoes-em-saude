# Aula 07

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/8011523/mod_resource/content/1/Aula%209%202023.pdf) utilizados na aula.

* [Artigo](https://dergipark.org.tr/en/download/article-file/1577402#:~:text=Our%20findings%20show%20that%20the,with%20slow%20and%20inconsistent%20performance.) referência da aula: *Comparison of Gradient Boosting Decision Tree Algorithms for CPU Performance*.

### **Aula**

Na aula, foram abordados os principais algoritmos de Machine Learning (ML) para dados estruturados. Destacam-se regressões penalizadas, redes neurais e algoritmos de árvore, como árvores de decisão, Random Forest e Gradient Boosting (XGBoost, LightGBM e CatBoost).

Random Forests utilizam uma técnica chamada bagging, que consiste em selecionar amostras aleatórias dos dados de treino, e incorporam seleção de preditores em cada nó por meio do sorteio de variáveis. Esse método ajuda a evitar o sobreajuste.

Regressões penalizadas, tanto linear quanto logística, geram predições e incluem penalizações para parâmetros elevados (betas) para minimizar erros. A penalização L2 (ridge) é escolhida por validação cruzada, reduzindo os betas sem atingir zero, enquanto a penalização L1 (Lasso) reduz os valores absolutos dos parâmetros, realizando seleção de variáveis ao tornar alguns betas zero.

Redes neurais, incluindo o conceito mais amplo de Deep Learning, também foram discutidas na aula, abordando a utilização de arquiteturas complexas para aprendizado de representações mais profundas e complexas em dados estruturados.

### **Artigo**

O artigo compara a implementação de algoritmos de Gradient Boosting Decision Trees (GBDT): XGBoost (o mais popular), LightGBM e CatBoost. O conceito de ensemble, onde várias árvores de decisão são criadas e votam para tomar decisões, é destacado. No GBDT, as árvores são sequenciais, aprendendo com os erros da árvore anterior, ao contrário do Random Forest, onde as árvores são independentes.

As árvores podem crescer por níveis (como no XGBoost) ou por folhas (como no LightGBM), com o limite de crescimento sendo um hiperparâmetro ajustável. Esses hiperparâmetros são essenciais para evitar sobreajuste, garantindo que os modelos aprendam padrões nos dados em vez de memorizá-los. Um exemplo de hiperparâmetro é o número de divisões permitido.

O LightGBM é destacado como o mais rápido, oferecendo um desempenho equilibrado em comparação com os outros algoritmos.
