# manutencao-preditiva-ai4i-2020
# Manutenção Preditiva com Ciência de Dados

## Objetivo
Aplicar técnicas de Ciência de Dados e Machine Learning para identificar padrões associados à ocorrência de falhas em máquinas.

## Base de dados
AI4I 2020 Predictive Maintenance Dataset, composta por 10.000 registros.

## Metodologia
- Análise exploratória dos dados.
- Preparação e verificação da consistência da base.
- Comparação entre DummyClassifier (baseline), Regressão Logística e Random Forest.
- Validação cruzada e otimização de hiperparâmetros.
- Avaliação final utilizando métricas de classificação.

## Principais resultados
A Random Forest otimizada apresentou:
- Acurácia: 98,25%.
- Precisão: 85,11%.
- Recall: 58,82%.
- F1-score: 0,6957.
- ROC-AUC: 0,965.

## Conclusão
Os resultados mostram o potencial do Machine Learning na manutenção preditiva, mas também evidenciam a necessidade de melhorar a identificação de falhas e validar o modelo com dados reais de operação.

## Tecnologias utilizadas
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
