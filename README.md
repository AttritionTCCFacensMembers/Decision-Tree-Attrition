# Decision-Tree-Attrition
Trabalho de conclusão do curso de Especialização em Data Science - Facens

O código consiste em 3 partes, sendo elas:

  1- Tratamento e exploração dos dados: nessa etapa nós tratamos os dados, fazemos a engenharia de atributos, tratamos os nulos e passamos pela análise exploratória.
  
  2- Pré-processamento e análise dos hiperparametros da árvore de decisão: Essa etapa acontece o estudo massivo dos hiperparametros da árvore de decisão. Foi construído um pipeline
  com todas as etapas de pré processamento e procuramos os melhores parametros através do gridsearch, fazendo um loop com todas as possíveis interações.
  
  3- Modelo Final: Essa etapa roda o algorítimo com os melhores parametros encontrados na parte 2 e exibe as métricas de desempenho.
  
  Como usar:
  
  -Caso queira reproduzir o código, rode a parte 1 que irá te retornar um dataframe tratado e ele será o input para as partes 2 e 3. 
  
  -A parte 2 é opcional pois demora cerca de 48hrs para executar todas as interações e irá retornar um arquivo (resultados gerais) com o catálogo de modelos.
  
  -A parte 3 irá gerar um modelo partindo dos melhore parametros encontrados na parte 2 (esses parâmetros ja estão selecionados no código para que não seja necessário rodar a parte2).
  
