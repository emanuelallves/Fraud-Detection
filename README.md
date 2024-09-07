# Projeto de Análise e Predição de Fraudes em Transações de Cartão de Crédito

Este projeto consiste em uma a análise exploratória e na criação de um modelo preditivo para prever futuras fraudes em transações de cartão de crédito. A análise exploratória (EDA) revelou insights valiosos sobre o comportamento das fraudes, enquanto o modelo preditivo foi ajustado para melhorar a detecção de fraudes.

## Análise Exploratória de Dados (EDA)

Durante a análise exploratória, foram identificados os seguintes padrões e insights:

- Problema significativo com fraudes: Observamos um padrão alarmante onde várias cidades enfrentam um problema significativo com fraudes, mas não registram nenhuma transação legal. Isso sugere que essas cidades podem estar sendo exploradas por atividades fraudulentas sem compensação positiva.

- Estados com mais transações fraudulentas: Estados com um número elevado de transações fraudulentas foram identificados, o que era esperado, considerando o volume total de transações. No entanto, dois estados, RI e DE, apresentaram um número significativo de fraudes apesar de terem poucas transações. Essa informação pode ajudar na detecção de fraudes.

- Influência da categoria na fraude: A categoria da transação tem uma influência significativa na probabilidade de fraude. As categorias 'grocery_pos', 'shopping_net', 'misc_net' e 'shopping_pos' foram destacadas por terem mais de 15 fraudes cada.

- Faixa de quantia de transação: A maioria das fraudes ocorre quando a quantia da transação está entre 130 e 890. Este insight pode ser crucial para o modelo preditivo.

## Dados do Modelo

O modelo preditivo foi avaliado em duas fases:

Primeiro Teste do Modelo:

Acurácia: 1.00
Recall Score: 0.59
Precision Score: 0.75
F1-Score: 0.66
Roc-Auc-Score: 0.79

Após Ajuste dos Parâmetros:

Acurácia: 0.77
Recall Score: 0.98
Precision Score: 0.02
F1-Score: 0.05
Roc-Auc-Score: 0.87
Os ajustes de parâmetros melhoraram significativamente o Recall Score e o Roc-Auc-Score, indicando uma melhoria na capacidade do modelo de identificar fraudes, embora a precisão tenha diminuído.
