# Aula 05

**Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7980632/mod_resource/content/1/Aula%207%202023.pdf) da aula.

* Artigo Referência da Aula: *Tour of evaluation metrics for imbalanced classification*.

**Aula e Artigo**

Na aula foram apresentados conceitos como: RMSE (raiz quadrada do erro quadrático médio), acurácia, classificação desbalanceada, classe minoritária, undersampling, oversampling, matriz de confusão, verdadeiro positivo, falso positivo, falso negativo, verdadeiro negativo, sensibilidade, especificidade, precisão, recall, F1-score, valor predito positivo, valor predito negativo, área abaixo da curva ROC, Brier Score e gráficos de calibração.

* Como fazer rebalanceamento (não é feito no teste!)

Down-sampling (under): a classe majoritária se iguala a minoritária

Up-sampling (over): a classe minoritária se iguala a majoritária

* Mensuração de qualidade (performance) é diferente entre regresão e classificação.

Para regressão utilizamos o RMSE e gráfico de dispersão da predição vs realidade.

Para classificação utilizamos: acurácia (proporção de acertos), análise de concordância visual (matriz de confusão), sensibilidade/recall (quantos dos positivos eu consigo acertar), especificidade (quantos dos negativos eu consigo acertar), precisão (dado que eu falei que é positvo, quantos desses são positivos de fato), F-score (combina precisão e recall), AUC (entre duas pessoas aleatórias - uma tem o desfecho e outra não - a AUC é a proporção de vezes que a predição será maior para a pessoa que de fato tem o desfecho. AUC > 0.7 é OK, AUC > 0.8 é bom, AUC > 0.9 excelente) e BrierSocre (o quanto calibrado (acerto das probabilidades) está o algoritmo. Quanto menor melhor) ou gráfico de calibração.

![image](https://github.com/claudiaanjos/ML-predicoes-em-saude/assets/84209593/9326d89f-56e2-45e8-8f25-a4ebbb2744db)

