# Data Science

## Pré processamento de dados

Operações realizadas nos dados para aplicação dos algorítmos de _machine learning_ da melhor forma possível.

+ Obter os dados e inserir no programa
     + Leitura de dados com o comando `data = pd.read(<fonte de dados>)`
     + Avaliar as colunas e ver se todas parecem pertinentes para a solução
          + Remover do conjunto de dados (caso não seja pertinente)[❌] 
+ Analisar features numéricas
     + Aplicar transformação logarítmica (caso a feature seja muito enviesada)[⚠️]
     + Normalizar os valores entre 0 e 1
+ One-hot encode variáveis categóricas (string, char, etc.) com `pandas.get_dummies()`
+ Embaralhar e dividir os dados
     + Este passo é realizado para que tenhamos dados de treinamento e dados de teste do nosso modelo
          + 80% para treinamento
          + 20% para testes
     