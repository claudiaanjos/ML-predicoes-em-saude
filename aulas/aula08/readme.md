# Aula 08

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/8011524/mod_resource/content/1/Aula%2011_2023.pdf) utilizados na aula.

* [Artigo](https://pubmed.ncbi.nlm.nih.gov/29045534/) referência da aula: *Evaluation of variable selection methods for Random Forest and Omics data sets*.

### **Aula**

Na aula, foram discutidas estratégias para a seleção de variáveis preditoras, com destaque para o algoritmo Boruta. Uma ideia central apresentada foi que os preditores não necessariamente precisam causar o desfecho, mas sim consistentemente predizê-lo.

O Boruta é um algoritmo utilizado para seleção de variáveis em problemas de aprendizado de máquina. Ele é projetado para identificar as variáveis mais importantes em conjuntos de dados, descartando aquelas que têm pouco impacto preditivo. Aqui estão alguns pontos-chave sobre o algoritmo Boruta:

* Objetivo Principal: O Boruta é frequentemente utilizado para problemas de classificação e regressão, onde o objetivo é prever uma variável de interesse (rótulo ou resposta) com base em um conjunto de variáveis preditoras.

* Método de Seleção: O algoritmo opera por meio de um processo de comparação. Ele compara as importâncias das variáveis originais com as importâncias de variáveis aleatórias (ruído). Se uma variável original tem uma importância significativamente maior do que as variáveis aleatórias, ela é considerada importante para o modelo.

* Uso de um Modelo de Árvore: O Boruta geralmente utiliza um modelo de árvore, como o Random Forest, para calcular a importância das variáveis. Esse modelo é treinado no conjunto de dados original e em versões aleatorizadas (com variáveis aleatórias) para fins de comparação.

* Critério de Decisão: O algoritmo utiliza um critério estatístico para decidir quais variáveis são importantes. As variáveis que têm uma importância significativamente maior do que as variáveis aleatórias são retidas, enquanto as outras são consideradas não importantes.

* Vantagens: O Boruta é útil para lidar com conjuntos de dados complexos, onde a relação entre variáveis e resultados pode não ser linear ou trivial. Ele ajuda a identificar as variáveis mais relevantes para a tarefa preditiva.

Em resumo, o Boruta é uma ferramenta valiosa para seleção de variáveis em problemas de aprendizado de máquina, especialmente quando se busca identificar as características mais importantes em meio a conjuntos de dados complexos.

### **Artigo**

O artigo compara diversas abordagens de seleção de variáveis para problemas de alta dimensionalidade, usando simulações e o algoritmo Random Forest (RF). As abordagens avaliadas incluem:

* Boruta: Classificado como o melhor, especialmente eficaz em baixas dimensionalidades.

* Vita: Considerado o segundo melhor, caracterizado por sua rapidez.

Outras abordagens analisadas incluem a importância variável relativa recorrente, permutação, Altmann e eliminação recursiva de variáveis. O estudo busca oferecer insights sobre a eficácia dessas estratégias em situações de alta dimensionalidade usando o RF como método de análise.


