# Aula 02

**Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7956028/mod_resource/content/1/Aula%202.pdf) da aula.

* [Artigo](https://neptune.ai/blog/data-preprocessing-guide) Referência da Aula: *A comprehensive guide to data preprocessing*.

**Aula**

Principais razões técnicas pelas quais algoritmos às vezes não apresentam boa performance preditiva:

- Extrapolação inadequada dos resultados
- **Pré-processamento** inadequado dos dados
- Sobreajuste (mais importante)
- Validação inadequada da qualidade dos algoritmos

**Pré-processamento dos dados**

- Seleção de variáveis preditoras plausíveis - não precisam causar o desfecho, mas associadas ao desfecho. Ex.: Predizer risco de morte - o fato de ter sido internado na UTI é importante (pois é grave), mas não é o causador.

- Vazamento de informação (“data leakage”) - os dados de treino apresentam informação escondida que faz com que o modelo aprenda padrões que não são do seu interesse. Ex.1: Uma variável que vem depois do desfecho (coletada depois), ela tem um resultado prévio do desfecho dentro dela. Ex.2: Incluir o número identificador do paciente como variável preditora.
- Padronização - as variáveis contínuas para todas terem média de 0 e desvio-padrão de 1.

- Redução de dimensão - Quanto maior a dimensão dos dados (número de variáveis) maior o risco de o algoritmo encontrar e utilizar associações espúrias. Ex.: PCA.

- Colinearidade - variáveis muito correlacionadas entre si (0.75 a 0.90), ou retira uma delas ou PCA.

- Missing - em predição, muitas vezes, é interessante ter variável faltante. Isso pode ser um preditor. Ex.1: No hospital que tem medição de altura, mas não conseguiram de todos = pode ser que esses pacientes são acamados. Teste cognitivo que o paciente não consegue responder. Ex.2: Em variável contínua faz a imputação e cria outra coluna categórica para indicar quem era missing.

- One-hot enconding - Alguns algoritmos têm dificuldade em
entender variáveis que têm mais do que uma categoria. Transforma em 0 e 1.

**Artigo**

Pré-processamento: método de análise, filtragem, transformação e codificação para que o algoritmo possa compreender os dados.

Parte considerável de um projeto: cerca de 80% do tempo

- Obtenha uma visão geral dos dados
- Identifique dados ausentes
- Identifique outliers e anomalias
- Remova inconsistências

