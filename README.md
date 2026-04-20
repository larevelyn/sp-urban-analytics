# sp-urban-analytics

# 📊 SP Urban Insights
Análise integrada de criminalidade, custo de aluguel e densidade populacional na cidade de São Paulo.

## 📌 Objetivo
Este projeto tem como objetivo identificar padrões e correlações entre:
- Taxas de criminalidade
- Preço de aluguel (R$/m²)
- Densidade populacional

A proposta é responder perguntas como:
- Existem regiões baratas e seguras?
- Regiões caras são necessariamente mais seguras?
- Como a densidade populacional impacta a criminalidade?

---

## 🧠 Abordagem
O projeto segue uma lógica analítica estruturada:

1. **Ingestão de dados**
   - Dados de criminalidade (SSP/SP)
   - Dados de aluguel
   - Dados populacionais (IBGE)

2. **Tratamento e padronização**
   - Normalização de nomes de bairros/distritos
   - Remoção de acentos e padronização textual
   - Tratamento de inconsistências entre bases

3. **Feature Engineering**
   - Taxa de crimes per capita
   - Preço por metro quadrado (R$/m²)
   - Normalização (Min-Max)
   - Classificações:
     - Periculosidade
     - Faixa de preço

4. **Análise**
   - Correlação entre variáveis
   - Segmentação por regiões (Centro, Zona Leste, etc.)
   - Identificação de clusters:
     - Barato & Seguro
     - Caro & Seguro
     - Barato & Perigoso
     - Caro & Perigoso

---

## 🛠️ Tecnologias utilizadas
- Python (Pandas, NumPy)
- PySpark
- Matplotlib / Seaborn
- Jupyter / Colab

---

## 📊 Principais métricas
- Taxa de crimes por habitantes
- Preço médio por m²
- Índices normalizados (0 a 1)

---

## 📍 Principais desafios
- Divergência de nomenclatura entre bairros e distritos
- Integração de múltiplas fontes de dados
- Outliers em preços de aluguel
- Falta de granularidade em alguns datasets

---

## 📥 Download dos dados

Os dados utilizados no projeto estão armazenados no Google Drive:

https://drive.google.com/drive/folders/1H5dTmGJVsSVL-nxUe4qe98lAhX6eqrN1

---

## 📬 Contato
Caso queira trocar ideias ou sugerir melhorias, fique à vontade para entrar em contato.
