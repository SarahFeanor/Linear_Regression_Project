[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Data Science - Sarah F. Rezende

## **Projeto** - ** Regressão Linear - Previsão das Variações das Ações da Google** 

[PROJETO (COLAB)](https://github.com/SarahFeanor/Churn_Prediction_Project/blob/main/Churn_Prediction.ipynb)

Bem-vindos(as). Este repositório foi criado com o propósito de estudo. Vale ressaltar que todos os dados são exclusivamente para fins de demonstração, garantindo total privacidade e conformidade ética.

<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1202653476228960306/download.jpg?ex=65ce3d54&is=65bbc854&hm=7c1cf49f358872342bf602e94c3ec8c85c0013939848c33a5d8da859ced3e92e&" alt="capa" width="600" height="300">
  </a>
</p> <p align="center"> <sup> Foto de Imagge </sup> </p>

## **Previsão das Variações das Ações da Google Utilizando a Regressão Linear para Maximizar Investimentos **

📊 Neste projeto, propomos empregar técnicas avançadas de análise, especificamente a **regressão linear**, para realizar **previsões** precisas das variações nas ações da **Google**. O principal propósito é auxiliar investidores a tomar decisões informadas e maximizar seus retornos financeiros. Ao aplicar a regressão linear aos dados históricos das ações da **Google**, iremos modelar as tendências e os padrões que podem influenciar os movimentos futuros do mercado.

A análise das ações da Google envolve um estudo profundo das flutuações de preços, considerando fatores como indicadores econômicos, eventos do setor de tecnologia, bem como notícias globais que impactam a empresa. Ao identificar correlações significativas entre esses fatores e o comportamento das ações, seremos capazes de criar um modelo preditivo confiável.

Com o objetivo de fornecer uma ferramenta valiosa aos investidores, vamos não apenas focar em prever os melhores momentos para comprar ou vender ações da Google, mas também em avaliar o risco associado a essas decisões. Compreender as incertezas envolvidas é crucial para uma estratégia de investimento sólida e bem-sucedida.

Este projeto é uma tentativa de combinar análise de dados, conhecimento financeiro e tecnologia para proporcionar insights acionáveis aos investidores interessados em ações da Google. Ao adotar abordagens inovadoras e empregar ferramentas estatísticas avançadas, buscamos capacitar os investidores a tomarem decisões informadas e, potencialmente, obterem vantagens competitivas nos mercados financeiros em constante evolução.

## 📍 **OBJETIVO**:
Utilizar a Regressão Linear para Prever as Melhores Oportunidades de Investimento nas Ações da Google

## **Carregando Dados**

* O código utiliza a biblioteca **yfinance** para adquirir informações sobre as ações da **Google** dentro do intervalo de datas definido.
* Uma vez que tenhamos carregado os dados históricos das ações da Google, calcularemos a variação diária das ações e adicionaremos uma coluna "Variation" ao DataFrame df. Isso nos dará uma base sólida para continuar com a análise e construção do modelo de regressão linear.

## Conclusão

Em conclusão, a série de previsões de variações diárias das ações para um futuro próximo oferece insights sobre como se espera que o comportamento das ações evolua em relação aos dias anteriores. Cada valor previsto, como 0.0800869049, representa uma expectativa de aumento de aproximadamente 8.00% no valor das ações no primeiro dia futuro, enquanto o valor subsequente, 0.0666068540, indica um aumento de cerca de 6.66% no segundo dia futuro, e assim por diante.

Estas previsões são geradas pelo modelo de regressão linear que foi treinado utilizando variáveis independentes normalizadas (Open, High, Low e Volume) como entradas e a variável alvo (Variation) como saída. O objetivo do modelo é capturar as relações entre essas variáveis para realizar previsões sobre as futuras variações das ações.



