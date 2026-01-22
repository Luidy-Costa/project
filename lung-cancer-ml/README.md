# 🫁 Lung Cancer Prediction (v0.2.0)

Este projeto é uma ferramenta de **Machine Learning** desenvolvida para auxiliar no diagnóstico precoce de câncer de pulmão. O sistema atua como um mecanismo de triagem, analisando sintomas clínicos e hábitos comportamentais para calcular a probabilidade de risco do paciente.

## Funcionalidades
O núcleo do projeto é o processamento dos dados do paciente e a utilização do algoritmo **Random Forest** para calcular se existe risco de câncer de pulmão.

Para garantir que essa previsão seja confiável, o sistema também realiza uma limpeza prévia nos dados, removendo registros que poderiam distorcer o resultado artificialmente.

## Sobre os Dados
O modelo foi treinado com base no dataset público **Survey Lung Cancer**.
* **Fonte:** [Survey Lung Cancer (Kaggle)](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer).

## Como Executar

### Ferramentas Necessárias
Certifique-se de ter o Python 3.x instalado. As dependências do projeto são:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter