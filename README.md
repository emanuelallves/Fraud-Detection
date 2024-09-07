# Projeto de Análise e Predição de Fraudes em Transações de Cartão de Crédito

Este projeto consiste em uma a análise exploratória e na criação de um modelo preditivo para prever futuras fraudes em transações de cartão de crédito. A análise exploratória (EDA) revelou insights valiosos sobre o comportamento das fraudes, enquanto o modelo preditivo foi ajustado para melhorar a detecção de fraudes.

## Análise Exploratória de Dados (EDA)

Durante a análise exploratória, foram identificados os seguintes padrões e insights:

- Problema Significativo com Fraudes: Observou-se um padrão alarmante onde várias cidades enfrentam um problema significativo com fraudes, mas não registram nenhuma transação legal. Isso sugere que essas cidades podem estar sendo exploradas por atividades fraudulentas sem compensação positiva.

- Estados com Mais Transações Fraudulentas: Estados com um número elevado de transações fraudulentas foram identificados, o que era esperado, considerando o volume total de transações. No entanto, dois estados, Rhode Island (RI) e Delaware (DE), apresentaram um número significativo de fraudes apesar de terem poucas transações. Essa informação pode ajudar na detecção de fraudes.

- Influência da Categoria na Fraude: A categoria da transação tem uma influência significativa na probabilidade de fraude. As categorias 'grocery_pos', 'shopping_net', 'misc_net' e 'shopping_pos' foram destacadas por terem mais de 15 fraudes cada.

- Faixa de Quantia de Transação: A maioria das fraudes ocorre quando a quantia da transação está entre 130 e 890. Este insight pode ser crucial para o modelo preditivo.
