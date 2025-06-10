# 📊 Análise de Sentimentos de Avaliações da Google Play Store

Este projeto realiza **mineração de texto** em avaliações de usuários da Google Play Store. Através de pré-processamento, análise de sentimentos e visualizações, buscamos extrair insights úteis sobre a percepção dos usuários em relação aos aplicativos.

---

## 🎯 Objetivo

- Limpar e tratar avaliações textuais de usuários.
- Identificar o **sentimento** (positivo, negativo ou neutro) das avaliações.
- Gerar **visualizações** como gráficos de distribuição de sentimentos e uma nuvem de palavras.

---

## 🧰 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [NLTK](https://www.nltk.org/)
- [TextBlob](https://textblob.readthedocs.io/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [WordCloud](https://amueller.github.io/word_cloud/)

---

## 📝 Etapas do Projeto

1. **Coleta de Dados**
   - Usamos um dataset disponível no Kaggle com avaliações traduzidas para inglês.

2. **Limpeza e Pré-processamento**
   - Conversão para minúsculas.
   - Remoção de pontuações e stopwords.

3. **Análise de Sentimentos**
   - Utilizamos `TextBlob` para classificar as avaliações como positivas, negativas ou neutras.

4. **Visualizações**
   - Gráfico de barras com a distribuição dos sentimentos.
   - Nuvem de palavras com os termos mais frequentes.

---

## 📊 Exemplo de Resultado

[Gráfico de Sentimentos](https://prnt.sc/0phepBbMXRNX)

---

## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/text-mining-googleplay.git
   cd text-mining-googleplay
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook:
   - Use o Jupyter Notebook ou Google Colab.
   - Arquivo: `text_mining_googleplay.ipynb`

---

## 🧠 Possíveis Melhorias

- Traduzir o projeto para análises em português.
- Substituir `TextBlob` por `VADER` ou modelos do Hugging Face para maior precisão.
- Criar um painel interativo com Streamlit.

---

## 📌 Dataset

Disponível no Kaggle:  
[Google Play Store Reviews Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---
