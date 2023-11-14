# Aula 11

### **Materiais**

* [Slides](https://edisciplinas.usp.br/pluginfile.php/7418119/mod_resource/content/1/Aula%2016.pdf) utilizados na aula.

* Artigos referência da aula:

  - [*Federated learning: Challenges, methods, and future directions*](https://arxiv.org/abs/1908.07873)

  - [*Online Learning: A Comprehensive Survey*](https://arxiv.org/abs/1802.02871)

**Aula**

Na aula falamos sobre as duas mais importantes técnicas para as aplicações de ML em saúde nos próximos anos: aprendizado federado e aprendizado online (contínuo).

**Aprendizado Federado**

- Permite treinar modelos em dados descentralizados, preservando a privacidade ao colaborar em várias fontes de dados na área da saúde

- É uma maneira de treinar modelos usando dados de diferentes lugares, como hospitais, sem precisar compartilhar esses dados. Isso ajuda a proteger a privacidade das informações de saúde

Exemplo: Imagine que existem diferentes hospitais, cada um com seus próprios dados de pacientes. Em vez de coletar todos esses dados em um único local (o que pode ser arriscado em termos de privacidade), o aprendizado federado permite que modelos de ML sejam treinados em cada hospital sem que os dados reais saiam de lá. Isso é feito através de técnicas que permitem que os modelos aprendam com esses dados localmente e compartilhem apenas informações agregadas ou pesos do modelo, protegendo assim a privacidade dos pacientes.


**Aprendizado Online**

- Atualiza modelos de ML continuamente com novos dados

- Os modelos são atualizados à medida que novos dados de saúde chegam, em vez de serem treinados em grandes lotes. Isso é útil para acompanhar as mudanças nas condições de saúde dos pacientes em tempo real

- Aprendizado no qual os dados chegam sequencialmente, e o preditor é atualizado em cada etapa

- Atualização instantânea do modelo (menor custo)

- Bons para aplicações em grande escala (tamanho e velocidade)

Em vez de treinar um modelo de ML apenas uma vez com um grande conjunto de dados e depois usá-lo estático, o aprendizado online envolve atualizar o modelo constantemente à medida que novos dados chegam. Por exemplo, um modelo de ML para monitorar pacientes pode se ajustar automaticamente sempre que novos dados, como leituras de sinais vitais, estiverem disponíveis. Isso permite que o modelo esteja sempre atualizado e adaptado às condições em evolução dos pacientes.
