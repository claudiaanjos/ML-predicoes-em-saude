# Aula 01

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7926382/mod_resource/content/1/Aula%201.pdf) utilizados na aula.

* [Artigo](https://arxiv.org/abs/2108.02497) referência da aula: *How to avoid machine learning pitfalls: a guide for academic researchers*.

* [Vídeo](https://www.youtube.com/watch?v=xxgp1Ehbuh4&ab_channel=HalflingWizard) sobre o artigo em inglês.

### **Aula**

**Aprendizado Supervisionado (Foco da dispciplina)**

Quando temos/queremos uma resposta certa.

Temos dois grupos:
- Classificação: quando tenho uma categoria. Ex.: A pessoa vai morrer daqui 5 anos: sim ou não.
- Regressão: predizer uma variável quantitativa. Ex.: Qual será seu IMC no próximo ano.

**Aprendizado Não Supervisionado**

Não tenho a resposta certa, procuramos agrupamentos nos dados. 
Ex.1: Quero agrupar pacientes com pacientes cardiovasculares.
Ex.2: Redução de dimensão, tenho 30 variáveis e quero transformar em três.

**Aprendizado Semi-Supervisionado**

Dados que tem resposta certa e outros que não tem. Ex.: Identificação de fotos do facebook.

**Aprendizado por Reforço**

Agente interage com um ambiente dinâmico. Ex.: Jogos (aprende jogando várias vezes).

**Inferência vs Predição**

Qual o objetivo da sua análise?

O foco da disciplina é predição.

**Fluxo**

Dados pré-processados ➜ Algoritmos ➜ Teste em dados novos (qualidade do algoritmo)

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


