
# 📈 Forecasting de Volatilidade com Modelos GARCH

Este projeto tem como objetivo analisar os retornos e prever a volatilidade de ações de grandes empresas de tecnologia, utilizando modelos econométricos — com foco especial em **ARCH** e **GARCH**. A análise é feita com dados históricos obtidos diretamente da API do Yahoo Finance (`yfinance`).

---

## 🧠 Objetivos

- Calcular retornos diários das ações de empresas como AAPL, MSFT, GOOGL, entre outras.
- Verificar a presença de heterocedasticidade nos dados financeiros.
- Ajustar modelos GARCH para prever a volatilidade dos retornos.
- Comparar previsões com a volatilidade realizada.

---

## 🛠️ Tecnologias e Bibliotecas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- yfinance
- arch (para modelos GARCH)
- Statsmodels

---

## 📊 Estrutura do Projeto

1. **Coleta de dados** com yfinance
2. **Cálculo de retornos percentuais**
3. **Análise exploratória**
   - Gráficos de preços e retornos
   - ACF/PACF
   - Teste de heterocedasticidade
4. **Modelagem**
   - Ajuste de modelos ARCH e GARCH
   - Previsão de volatilidade
5. **Conclusão**
   - Avaliação da performance do modelo
   - Aplicações em finanças e gestão de risco

---

## 📎 Como Executar

1. Clone este repositório.
2. Instale as dependências:
   ```bash
   pip install yfinance arch pandas matplotlib seaborn statsmodels
   ```
3. Execute o notebook `analise_retorno_volatilidade_reestruturado.ipynb`.

---

## ✍️ Autor

Desenvolvido por [Leonardo Campos](https://www.linkedin.com/in/leonardocarcampos/), Business Intelligence Analyst em transição para Data Science.
