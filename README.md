# Regressão Multivariável com Redes Neurais Artificiais (RNA)

A **Regressão Multivariável** com Redes Neurais Artificiais (RNAs) é uma abordagem usada para prever **mais de uma variável contínua ao mesmo tempo**. Isso é útil em problemas onde diversas saídas numéricas estão relacionadas ao mesmo conjunto de entradas.

As RNAs são capazes de capturar **relações não lineares complexas** entre múltiplas variáveis de entrada e múltiplas saídas, sendo úteis em aplicações como previsão de indicadores financeiros, desempenho esportivo, vendas, entre outros.

### Por que usar RNA para regressão multivariável?

- Permite prever **vários alvos simultaneamente**
- Captura **correlações entre variáveis de saída**
- Reduz tempo computacional ao treinar um único modelo ao invés de vários
- Ideal para contextos multidimensionais com interdependência entre saídas

### Funcionamento Intuitivo

Imagine um modelo que, com base nas informações de um jogo (plataforma, marketing, nota de crítica), consegue prever **vendas na América do Norte, Europa e Japão ao mesmo tempo**. A rede aprende a mapear os dados de entrada para todas essas saídas de forma coordenada.

---

## 📂 Estrutura do Notebook

### `RNA1_Regressao_Multivariavel_Games_Orlando.ipynb`
**📌 Tarefa:** Prever múltiplos valores de vendas regionais para jogos  
**📚 Dataset:** Base de dados de jogos eletrônicos com vendas por região  
**🔍 Destaques:**
- Arquitetura com múltiplos neurônios de saída
- Normalização dos dados de entrada e saída
- Avaliação conjunta dos erros por região
- Visualização dos resultados reais vs. previstos

---

## 📈 Métricas e Avaliação

As RNAs de regressão multivariável foram avaliadas com:

- **MAE, MSE e RMSE por saída**
- **R² para cada variável de destino**
- **Gráficos comparativos para cada região/variável**
- **Análise do erro total multivariado**

---

## ⚙️ Técnicas Utilizadas

- Funções de ativação ReLU (oculta) e linear (saída)
- Otimizador Adam
- Normalização com `MinMaxScaler`
- Visualização com `Matplotlib` e `Seaborn`
"""
