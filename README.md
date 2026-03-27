# Previsão_Demanda_Sorvete

📊 Projeto de Análise de Demanda com Regressão Linear
📌 Sobre o Projeto

Este projeto tem como objetivo analisar o comportamento da demanda de um produto com base em variáveis como preço, temperatura, umidade e dia da semana, além de construir um modelo preditivo capaz de estimar a demanda futura.

A análise foi dividida em três etapas principais:

Limpeza de dados
Análise exploratória (EDA)
Modelagem com regressão linear
🧹 1. Limpeza de Dados

Nesta etapa, os dados foram tratados para garantir qualidade e consistência:

Remoção de símbolos (R$, °C, %, etc.)
Conversão de tipos para formato numérico
Tratamento de valores inválidos (ex: umidade fora do padrão)
Preenchimento de valores ausentes com mediana
Remoção de duplicidades

📌 Resultado: Dataset limpo e pronto para análise

📊 2. Análise Exploratória (EDA)

A análise exploratória permitiu entender os padrões e relações entre as variáveis.

🔍 Principais Insights:
A demanda varia significativamente, não sendo constante
Existe relação inversa entre preço e demanda
A temperatura impacta positivamente o consumo
A umidade pode reduzir a demanda
O comportamento é influenciado por fatores externos

📌 Conclusão da etapa: A demanda pode ser explicada por variáveis mensuráveis, o que torna viável a modelagem preditiva.

🤖 3. Modelagem (Regressão Linear)

Foi aplicado um modelo de regressão linear para prever a demanda.

📈 Variáveis utilizadas:
Preço
Temperatura
Umidade
📊 Métricas do modelo:
R²: 0.9998
MAE: 0.70
RMSE: 0.80
🔍 Interpretação:
O modelo apresenta altíssima precisão
Preço impacta negativamente a demanda
Temperatura impacta positivamente
Possível alerta de overfitting (modelo muito ajustado)
🚀 Conclusão

O projeto demonstrou que a demanda pode ser explicada e prevista com base em variáveis como preço e clima. A análise revelou padrões claros de comportamento do consumidor, e o modelo preditivo apresentou excelente desempenho.

Esses resultados mostram como a análise de dados pode apoiar decisões estratégicas, como:

Definição de preços
Planejamento de estoque
Previsão de vendas

⚠️ Apesar do alto desempenho, é importante validar o modelo com novos dados para garantir sua generalização.

🛠️ Tecnologias Utilizadas
Python
Pandas
Matplotlib
Scikit-learn
