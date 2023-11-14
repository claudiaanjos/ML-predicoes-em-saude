# Aula 01

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7926382/mod_resource/content/1/Aula%201.pdf) utilizados na aula.

* [Artigo](https://arxiv.org/abs/2108.02497) referência da aula: *How to avoid machine learning pitfalls: a guide for academic researchers*.

* [Vídeo](https://www.youtube.com/watch?v=xxgp1Ehbuh4&ab_channel=HalflingWizard) sobre o artigo em inglês.

### **Aula**

Na disciplina, o foco principal é o Aprendizado Supervisionado, onde se busca uma resposta certa. Isso se divide em dois grupos: Classificação, quando a resposta é uma categoria (como prever se alguém morrerá nos próximos 5 anos), e Regressão, que envolve a previsão de uma variável quantitativa (por exemplo, o IMC no próximo ano).

O Aprendizado Não Supervisionado entra em cena quando não se tem a resposta certa, buscando padrões nos dados, como agrupar pacientes com condições cardiovasculares ou reduzir a dimensão das variáveis.

O Aprendizado Semi-Supervisionado lida com conjuntos de dados que possuem respostas para alguns casos e não para outros, como na identificação de fotos no Facebook.

O Aprendizado por Reforço envolve a interação de um agente com um ambiente dinâmico, comum em jogos, onde o agente aprende por meio de repetidas interações.

A disciplina destaca a diferença entre Inferência e Predição, sendo o foco principal a predição. O processo envolve dados pré-processados, aplicação de algoritmos e teste em dados novos para avaliar a qualidade do algoritmo.

### **Artigo**

1 - Antes de começar a construir modelos

* Entenda os dados
* Não olhe para todos os seus dados (teste x treino)
* Certifique-se de que há dados suficientes
* Converse com especialistas no assunto
* Levantamento da literatura
* Pensar em como o modelo será utilizado no mundo real

2 - Como construir modelos confiáveis

* Impeça vazamento de dados pro teste
* Teste vários modelos
* Não use modelos inapropriados
* Otimize hiperparâmetros
* Cuidado com otimização de hiperperâmetros e seleção de variáveis

3 - Como avaliar modelos

* Use um conjunto de teste adequado
* Use um conjunto de validação
* Avalie o modelo várias vezes
* Salve dados para uma avaliação final
* Não use a acurácia com dados desbalanceados

4 - Como comparar modelos

* Não presuma que valores maiores signifiquem modelos melhores
* Use teste estatísticos para comparar modelos (prof. é contra)
* Faça correções para múltiplas comparações
* Nem sempre acredite em resultados já encontrados em outros trabalhos
* Considere combinações de modelos

5 - Como relatar resultados

* Seja transparente
* Relate o desemprenho de várias formas
* Não generalize para além do seu conjunto de dados
* Cuidado ao relatar significância estatística
* Olhe seus modelos


