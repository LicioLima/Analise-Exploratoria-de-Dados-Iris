# 🌸 Análise Exploratória de Dados — Iris Dataset

## 📖 Contexto do Projeto

Este projeto foi desenvolvido como parte do **Módulo 1 do Bootcamp de Engenharia de Dados**.

Nele, assumi o papel de **Consultor(a) Principal** da empresa fictícia **Dados Mágicos Ltda.**, com o objetivo de demonstrar aos stakeholders como a **Análise Exploratória de Dados (EDA)** é essencial para apoiar decisões estratégicas e preparar dados para futuros modelos preditivos.

A análise utiliza o famoso **Iris Dataset**, considerado o *“Hello World”* da Ciência de Dados, contendo métricas físicas de três espécies de flores íris:

- Setosa
- Versicolor
- Virginica

---

# 🎯 Objetivos de Aprendizado

Este projeto exercita conceitos fundamentais da **Modern Data Stack** e das boas práticas de desenvolvimento em dados, incluindo:

- Fundamentos de Engenharia de Dados
- Ingestão e preparação de dados
- Boas práticas de desenvolvimento em Python
- Versionamento e organização de código
- Análise Exploratória de Dados (EDA)
- Extração de insights estatísticos
- Visualização de dados

---

# 🛠️ Tecnologias e Ferramentas

## Linguagem
- Python

## Bibliotecas de Manipulação
- Pandas  
  - DataFrames
  - Inspeção de dados
  - Limpeza de dados

## Bibliotecas de Visualização
- Seaborn
- Matplotlib

## Ambiente de Desenvolvimento
- Google Colab
- Jupyter Notebook

---

# 📈 Etapas da Implementação Técnica

A análise foi conduzida seguindo um fluxo estruturado de engenharia de dados para garantir confiabilidade e qualidade das informações.

## 1️⃣ Ingestão e Inspeção dos Dados

- Carregamento do arquivo CSV
- Visualização inicial com:
  - `head()`
  - `info()`
  - `describe()`

---

## 2️⃣ Qualidade dos Dados

- Verificação de valores nulos com:
  - `isnull()`
- Análise do balanceamento entre espécies:
  - `value_counts()`

---

## 3️⃣ Visualização Estatística

### 🔹 Scatterplots e Pairplots
Utilizados para identificar:
- Relações entre variáveis
- Agrupamentos naturais das espécies
- Separabilidade dos dados

### 🔹 Histogramas e Distplots
Aplicados para compreender:
- Distribuição de frequência
- Comportamento estatístico das variáveis

### 🔹 Heatmap de Correlação
Uso da **Correlação de Pearson** para identificar relações entre atributos numéricos.

### 🔹 Boxplots
Ferramenta essencial para:
- Identificação de outliers
- Detecção de valores discrepantes
- Preparação para futuras modelagens

---

# 🚀 Como Executar

Este projeto está disponível no formato `.ipynb`.

Você pode executá-lo diretamente em:

- Google Colab
- Jupyter Notebook
- VS Code com extensão Jupyter

## Dependências necessárias

```bash
pip install pandas matplotlib seaborn
