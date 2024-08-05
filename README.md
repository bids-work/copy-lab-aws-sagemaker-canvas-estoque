## Bootcamp Nexa - Machine Learning para Iniciantes na AWS


📊 Previsão de Estoque Inteligente na AWS com SageMaker Canvas


🎯 Objetivos Deste Desafio de Projeto (Lab)

🚀 Passo a Passo

**1. Selecionar dataset**

A partir do repositório [https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque], selecionado o arquivo /(https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/dataset-1000-com-preco-promocional-e-renovacao-estoque.csv) para treinar o modelo de previsão de estoque e feito upload no SageMaker Canvas.



**2. Construir e Treinar**

Importado o conjunto de dados no SageMaker Canvas e realizado treinamento do modelo.

![screenshot do dataset selecionado](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Select.PNG)
![screenshot do modelo](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/SageMakerCanvas%20-%20My%20Models%20-%20Estoque_2.PNG)



 **3. Analisar**

Após o treinamento do modelo, as principais análises das métricas identificadas foram:

Avg. wQL: 0.018; indicando que o desvio padrão apresenta variabilidade, mas não são excessivamente dispersos, sendo desejável o mais próximo de 0 (zero);
MAPE: 0.021; que tem uma previsão de erro de 2,1%, e quanto menor, mais precisa é a previsão;
WAPE: 0.020; previsão de erro de 2% em relação aos números reais, portanto, uma métrica útil para avaliar a precisão das previsões.
RMSE: 3.475
MASE: 0.700; que necessitam de outras bases comparativas para um parecer mais preciso.

![screenshot do model status do SageMaker Canvas](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Analyze_print.PNG)



**4. Prever**

Utilizado modelo treinado para o estoque selecionado, as principais análises foram:
Nas análises preditivas de items, por exemplo, o item 1000, apresentou P10, P50 e P90, com as previsões pessimista, média/provável ou otimista, respectivamente: 132.177, 153.809 e 153.997.
Assim como pode-se realizar com cada item separadamente. Tanto em expressão numérica quanto gráfica. Além de outras leituras como por Correlation Matrix, Scatter plot, Bar chart, a partir de cada coluna.

![screenshot do single prediction do item 1000](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Predict_01.PNG)
![screenshot do single prediction do item 1000 - gráfico](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Predict_02.PNG)

![screenshot do single prediction do item 1014](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Predict_04.PNG)
![screenshot do single prediction do item 1014 - gráfico](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Predict_03.PNG)

![screenshot do build](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Build_print.PNG)
![screenshot do bar chart](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Bar%20Chart.PNG)
![screenshot do bar chart columns](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Bar%20Columns.PNG)
![screenshot do correlation matrix](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Matrix.PNG)



**5. Observações**

Gostaria de prosseguir para novos treinamentos, testes e análises, mas considerando os comentários no Forum, e também ocorreu comigo, mesmo restringindo e ativando o budget para uso gratuito, a AWS já está informando que extrapolei a quota de uso e cobrança. Portanto, para não gerar outras cobranças adicionais, optei por suspender (logout) o uso do SageMaker Canvas para evitar novas cobranças não programadas.

![screenshot do Free Tier](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Free%20Tier.PNG)
![screenshot do Gerenciador de orçamento](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Gerenciador%20de%20orcamento.PNG)
![screenshot do OverQuota da AWS](https://github.com/bids-work/copy-lab-aws-sagemaker-canvas-estoque/blob/main/AWS%20Quotas.png)



**6. Conclusão**

A ferramenta e o conteúdo do curso foram bastante interessantes e importantes, mas pretendo aprofundar nos testes e uso do SageMaker Canvas em outras oportunidades quando tiver orçamento destinado para esta prática. Quanto ao Desafio de Projeto, apesar de interessante, poderia ter outra metodologia que não gerasse custos adicionais, ou uma desejável parceria com a AWS para os alunos da DIO no decorrer do Bootcamp.




