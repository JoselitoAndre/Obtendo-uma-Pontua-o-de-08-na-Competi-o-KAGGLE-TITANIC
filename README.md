Obtendo uma Pontuação de 0,8 na Competição KAGGLE TITANIC

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSGg1RhFxYx-s7lX2ybsXRFLfoUtKbRwUa9hOgGCucXR1PDBZ9DEg&s)


# O que é o Kaggle?

O [kaggle.com](http://kaggle.com) é uma plataforma onde as pessoas criam algoritmos contribuindo e competindo com profissionais de aprendizado de máquina em todo o mundo. O algoritmo vencedor será o mais preciso em um conjunto de dados específicos. O Kaggle é uma maneira divertida de praticar suas habilidades de aprendizado de máquina com dados do mundo real.

Existe no Kaggle uma série de competições desenvolvidas para iniciantes. Uma das mais populares e a que veremos é sobre a previsão de quais passageiros sobreviveram ao naufrágio do Titanic.

Nesta competição, temos um conjunto de dados de informações diferentes sobre passageiros a bordo do Titanic e veremos se poderemos usar estas informações para prever se essas pessoas sobreviveram ou não.


# Entendendo o Data Sete.


As competições do Kaggle, geralmente possuem dois arquivos de dados distintos, sendo um conjunto de treinamento e um conjunto de testes.
  
Os arquivos que lemos no bloco anterior estão disponíveis na [página de dados da competição Titanic no Kaggle](https://www.kaggle.com/c/titanic/data). Essa página também possue um dicionário de dados, que explica as várias colunas que compõem o conjunto de dados. Abaixo estão contidas as descrições do dicionário de dados:
 

- PassengerID - Uma coluna adicionada pelo Kaggle para identificar cada linha e facilitar os envios.

- Survived - se o passageiro sobreviveu ou não e o valor que estamos prevendo (0 = Não, 1 = Sim).

- Pclass - A classe do bilhete que o passageiro comprou (1 = 1º, 2 = 2º, 3 = 3º).

- Sex - O sexo do passageiro

- Age - A idade do passageiro em anos

- SibSp - O número de irmãos ou cônjuges que o passageiro tinha a bordo do Titanic

- Parch - O número de pais ou filhos que o passageiro tinha a bordo do Titanic

- Ticket - O número do bilhete do passageiro

- Fare - A tarifa paga pelo passageiro

- Cabin - O número da cabine do passageiro

- Embarked - O porto em que o passageiro embarcou (C = Cherbourg, Q = Queenstown, S = Southampton)

A página de dados no Kaggle tem algumas notas adicionais sobre algumas das colunas. Sempre vale a pena explorar isso em detalhes para obter um entendimento completo dos dados.

