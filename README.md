# Projeto de Machine Learning: Average car prices - Brazil
**Dataset Kaggle:** [Average car prices - Brazil](https://www.kaggle.com/datasets/vagnerbessa/average-car-prices-bazil/data) <br>
**Meu projeto no Kaggle:** [Link do meu projeto](https://www.kaggle.com/code/nerdygames/machine-learning-average-car-prices-brazil) <br>
**Autor:** Bruno Pereira <br>

---
🎯 **Objetivo do projeto:** Meu objetivo com este projeto é a criação de um modelo de regressão para conseguir fazer a previsão dos preços médio dos carros utilizando a linguagem Python. Para isso foi necessário o treinamento de dois modelos para descobrimos o que obtivesse melhor desempenho para poder faremos as previsões. Utilizei conceitos como: **Tuning dos parâmetros**, **Validação cruzada**, etc. Além de deixar os códigos o mais claro possível para facilitar a compreensão do público não técnico. <br>

🎲 **Sobre o Dataset:** A base de dados consiste no preço médio dos carros do Brasil segundo a tabela FIPE, as pesquisas foram feitas durantes os anos de 2021 e 2023. Cada linha corresponde a uma pesquisa do preço médio de um carro.  Utilizei como guia os conceitos ensinados pela **EBAC**(*Escola Britânica de Artes e Tecnologia*), do livro: **Estatística Prática para Cientistas de Dados**(*Autores: Peter Bruce & Andrew Bruce*) e principalmente do curso da Udemy: **Machine Learning e Data Science com Python de A a Z**(*Professor: Jones Granatyr*).

🔎 **Explicação sobre o Notebook:** Dividi este notebook para melhor compreensão em 5 tópicos:
  1. Contexto: Breve explicação sobre meu objetivo, e sobre a base de dados;
  2. Pacotes, Bibliotecas & Importações: Importação das bibliotecas que serão utilizadas, assim como a definição de algumas funções que criei para evitar o reuso de código;
  3. Exploração inicial dos dados: Entendimento inicial da base de dados;
  4. Wrangling: Tratamento e limpeza para que os dados fiquem prontos para serem analisados;
  5. Machine Learning: A análise exploratória de fato, com várias visualizações, tabelas, conceitos estatísticos, etc. <br>
     1. Algoritmo: DecisionTreeRegressor - Explicação básica de como efetuar o treinamento do modelo DecisionTreeRegressor, como descobrir os atributos com melhor relevância, além de como avaliar os resultados;
     2. Algoritmo: RandomForestRegressor - Explicação básica de como efetuar o treinamento do modelo RandomForestRegressor, como descobrir os atributos com melhor relevância, além de como avaliar os resultados;
     3. Tunning dos Parâmetros - Descobriremos os melhores parâmetros de ambos os modelos para turbinarmos ainda mais os resultados do nosso modelo;
     4. Validação cruzada - Utilizaremos a validação cruzada para avaliar o desempenho dos modelos em diferentes subconjuntos dos dados e chegarmos a um veredito... qual o melhor modelo?
     5. Prevendo🪄 - Agora que sabemos qual algoritmo obteve o melhor desempenho, faremos uma previsão do preço médio de um modelo da Honda que não existe.

📊 **Alguns trechos do meu projeto:**

![Imagem com a execução de uma função que retorna algumas métricas sobre o desempenho do modelo além da explicação dos resultados](https://github.com/user-attachments/assets/64680ae1-8ad1-4c81-bc1a-c46f7e509a71)

![Explicação dos resultados da plotagem de uma árvore de decisão](https://github.com/user-attachments/assets/22af3aa1-7ced-43da-b5da-5ac56522b108)
