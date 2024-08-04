## Curso
Bootcamp Nexa - Machine Learning para Iniciantes na AWS


📊 Previsão de Estoque Inteligente na AWS com SageMaker Canvas


🎯 Objetivos Deste Desafio de Projeto (Lab)

🚀 Passo a Passo

**1. Selecionar conjunto de dados**

A partir do repositório [https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque], selecionado o arquivo dataset-1000-com-preco-promocional-e-renovacao-estoque.csv para treinar o modelo de previsão de estoque e feito upload no SageMaker Canvas.

**2. Construir/Treinar**

Importando o conjunto de dados no SageMaker Canvas e realizado treinamento do modelo.

 **3. Analisar**

Após o treinamento, as principais análises das métricas foram:
Avg. wQL: 0.018; indicando que o desvio padrão apresenta variabilidade, mas não são excessivamente dispersos;
MAPE: 0.021; que tem uma previsão de erro de 2,1%;
WAPE: 0.020; com 2% em relação aos números reais, portanto, uma métrica útil para avaliar a precisão das previsões.
RMSE: 3.475
MASE: 0.700

![screenshot da tela de model status do SageMaker Canvas] (https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Analyze_print.PNG)

**4. Prever**

Utilizado modelo treinado para o estoque específico, as principais análises foram:
Nas análises preditivas de items, por exemplo, o item 1000, apresentou P10, P50 e P90, com as previsões pessimista, média/provável ou otimista, respectivamente: 132.177, 153.809 e 153.997.
Assim como pode-se realizar com cada item separadamente. Tanto em expressão numérica quanto gráfica. Além de outras leituras como por Correlation Matrix, Scatter plot, Bar chart, a partir de cada coluna.

**5. Observações**

Gostaria de prosseguir para novos treinamentos, testes e análises, mas considerando os comentários no Forum, e também ocorreu comigo, mesmo restringindo e ativando o budget para uso gratuito, a AWS já está informando que extrapolei a quota de uso e cobrança. Portanto, para não gerar outras cobranças adicionais, optei por suspender o uso do SageMaker Canvas para evitar novas cobranças não programadas.

**6. Conclusão**

A ferramenta e o conteúdo do curso foram bastante interessantes e importantes, mas pretendo aprofundar nos testes e uso do SageMaker Canvas em outras oportunidades quando tiver orçamento destinado para esta prática. Quanto ao Desafio, apesar de interessante, poderia ter outra metodologia que não gerasse custos adicionais, ou uma desejável parceria com a AWS para os alunos da DIO no decorrer do Bootcamp.




