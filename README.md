# Exploração e Previsão com Dados de Rotatividade Bancária

Projeto da UC Análises Descritivas e Modelos Analíticos para problemas de negócios.

<br>

## Introdução

O projeto é uma análise de dados que deve conter as seguintes etapas:

- Carregar e ler arquivos .csv, xlsx ou de um banco de dados;
- Avaliar a necessidade da transformação da variável em outra escala (agrupar idade por faixas, por exemplo);
- Realizar a codificação das variáveis categóricas de acordo com os valores das variáveis (label encoder, one hot encoder ou target encoder);
- Normalizar as variáveis;
- Avaliar a necessidade de realizar o balanceamento da variável alvo;
- Tratar variáveis com alta correlação;
- Realizar a seleção de variáveis;
- Aplicar um modelo de regressão ou classificação utilizando uma técnica de hiperparametrização automática;
- Aplicar uma medida de avaliação do modelo.
- Gerar uma visualização para o resultado de acordo com os tipos abaixo:
  - Agrupamento: gerar a visualização Scatter;
  - Classificação: gerar a matriz de confusão;
  - Regressão: gerar a visualização da linha de saída.

<br>

### Backgroud dos Dados :bookmark_tabs:

Um gerente de banco está triste porque cada vez mais clientes estão abandonando os serviços de cartão de crédito. Eles realmente apreciariam se alguém pudesse prever quem terá uma deficiência, para que possam entrar em contato proativamente com os clientes para fornecer um serviço melhor e orientar as decisões dos clientes na direção oposta.

  - Atualmente este conjunto de dados inclui 10.000 clientes mencionando idade, salário, estado civil, limite do cartão de crédito, categoria do cartão de crédito, etc.
  - Existem quase 18 recursos.
  - Tivemos apenas 16,07% de abandono de clientes. Portanto, é um pouco difícil treinar nosso modelo para prever a rotatividade de clientes.

<br>

## Materiais :bookmark_tabs:

- **README:** Entendendo o projeto;
- **BankChurners.csv:** Dados do projeto;
- **notebook_dev.ipynb:** Notebook de desenvolvimento do projeto;

<br>

## Softwares e Programas :computer:

- JupyterNotebook

<br>

## Linguagens e Metodologia :pencil:

- Python
  - Sklearn
  - Proplot
  - Pandas
  - Numpy
  - Matplotlib
  - Seaborn
  - Scipy
  - Imblearn

<br>

## Considerações finais :mortar_board:

Fazer esse projeto foi uma experiência extremamente gratificante e desafiadora para mim. Lidar com dados desbalanceados era um território conhecido, por ser engenheira de dados, mas seguindo a perspectiva da ciência de dados e com o proposito de ML foi algo novo, mas encarei isso como uma oportunidade para adquirir novos conhecimentos e aplicar técnicas avançadas de pré-processamento de dados, como o SMOTE.

Explorar a Análise de Componentes Principais (PCA) foi interessante. Conseguir reduzir a dimensionalidade do conjunto de dados sem perder informações cruciais representou um avanço significativo para mim. Além disso, aprofundar-me no impacto do agrupamento (clustering) na precisão do modelo preditivo foi uma jornada estimulante de experimentação e descoberta, muito útil para meu trabalho.

<br>
 
## Fontes :point_left:

- https://scikit-learn.org/0.21/modules/clustering.html#clustering
- https://scikit-learn.org/0.21/modules/decomposition.html#pca
- https://scikit-learn.org/0.21/modules/preprocessing.html#preprocessing
- https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjK5sn5oNKGAxVAr5UCHVWcI2cQFnoECBkQAQ&url=https%3A%2F%2Fimbalanced-learn.org%2Fstable%2Fover_sampling.html&usg=AOvVaw1ZD7XAVgZ8NoRh0poaNiLk&opi=89978449
- https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiPmP2bodKGAxVKrpUCHfftDJQQFnoECAYQAQ&url=https%3A%2F%2Fdocs.scipy.org%2Fdoc%2Fscipy%2Freference%2Fstats.html&usg=AOvVaw10tRCONK2ao9l4hTVRvwig&opi=89978449

