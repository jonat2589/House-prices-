# House-prices-

1. Introdução e Objetivo do Projeto
Contexto: Este projeto visa prever os preços de venda de imóveis, auxiliando na análise de tendências de mercado e possíveis ajustes nos preços oferecidos.
Objetivo: Construir um modelo preditivo para estimar o preço de venda com alta precisão, aplicando três algoritmos de aprendizado de máquina: Regressão Linear, Árvore de Decisão e KNN.
2. Metodologia
Base de Dados:
Os dados foram extraídos de uma base contendo informações variadas sobre características dos imóveis.
Houve tratamento de valores ausentes e exclusão de colunas com mais de 10% de dados ausentes para garantir a qualidade do modelo.
Modelos Utilizados:
Regressão Linear: Modelo que analisa a relação entre as variáveis independentes e o preço de venda.
Árvore de Decisão: Modelo que faz previsões com base em árvores de decisões, útil para detectar interações não-lineares.
KNN (K-Nearest Neighbors): Modelo baseado em proximidade, que considera os imóveis mais similares para estimar o preço.
3. Resultados e Análise de Desempenho
A avaliação dos modelos foi feita usando MAE (Erro Médio Absoluto) e MSE (Erro Quadrático Médio), medindo a precisão e robustez das previsões.
Desempenho dos Modelos:
Regressão Linear: MAE: XX, MSE: YY
Árvore de Decisão: MAE: XX, MSE: YY
KNN: MAE: XX, MSE: YY
Análise dos Resultados: A Regressão Linear apresentou melhor desempenho para dados com relações mais lineares, enquanto a Árvore de Decisão e o KNN foram eficazes para capturar relações mais complexas entre as variáveis.
4. Visualizações e Análise Gráfica
Gráficos de Dispersão: Os gráficos mostram a correlação entre os valores previstos e os reais, indicando a precisão visual de cada modelo.
Insights Visuais: O modelo de Regressão Linear apresentou uma distribuição mais alinhada à linha de previsão ideal (linha vermelha), enquanto o KNN e a Árvore de Decisão apresentaram maior dispersão, indicando potencial ajuste adicional.
5. Conclusões e Recomendações
Melhor Modelo: O modelo de Regressão Linear demonstrou melhor estabilidade e precisão nos dados analisados.
Aplicação Prática: Implementar este modelo na estimativa de preços dos imóveis pode trazer melhor alinhamento dos preços com as condições do mercado.
Próximos Passos: Avaliar o desempenho do modelo com dados mais recentes para ajuste contínuo e considerar a combinação dos modelos (ensemble) para maior precisão.
