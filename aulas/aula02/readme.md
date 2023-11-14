# Aula 02

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7956028/mod_resource/content/1/Aula%202.pdf) utilizados na aula.

* [Artigo](https://neptune.ai/blog/data-preprocessing-guide) referência da aula: *A comprehensive guide to data preprocessing*.

### **Aula**

As principais razões técnicas para uma performance preditiva insatisfatória de algoritmos incluem:

* Extrapolação inadequada dos resultados
* Pré-processamento inadequado dos dados
* Sobreajuste (importante)
* Validação inadequada da qualidade dos algoritmos

No que diz respeito ao pré-processamento dos dados, algumas considerações essenciais são:

* Seleção de variáveis preditoras plausíveis: Variáveis associadas ao desfecho, não necessariamente causadoras.

* Vazamento de informação ("data leakage"): Evitar dados de treino com informações que não estarão disponíveis no uso prático do modelo.

* Padronização: Normalização das variáveis contínuas para média zero e desvio-padrão um.

* Redução de dimensão: Utilização de técnicas como PCA para evitar associações espúrias em conjuntos de dados de alta dimensão.

* Colinearidade: Gerenciamento de variáveis altamente correlacionadas (0.75 a 0.90), seja removendo uma delas ou usando técnicas como PCA.

* Missing: Consideração do valor faltante como um possível preditor, destacando a importância de interpretar a ausência de dados.

* One-hot encoding: Transformação de variáveis categóricas com mais de uma categoria em representações binárias (0 e 1) para melhor compreensão por certos algoritmos.


### **Artigo**

O pré-processamento refere-se ao método de análise, filtragem, transformação e codificação dos dados para que um algoritmo de machine learning possa compreendê-los. Constitui uma parte substancial de um projeto, consumindo cerca de 80% do tempo total. As etapas-chave incluem a obtenção de uma visão geral dos dados, identificação de dados ausentes, detecção de outliers e anomalias, e remoção de inconsistências para garantir que os dados estejam prontos para serem utilizados de maneira eficaz pelos algoritmos de Machine Learning.

