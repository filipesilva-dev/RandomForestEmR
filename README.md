# Random Forest - Diagnóstico de Doença Cardíaca em R

Projeto de Machine Learning utilizando o algoritmo Random Forest para prever doenças cardíacas com base em dados clínicos.

## Tecnologias Utilizadas

- R
- RStudio
- caret
- randomForest
- ggplot2
- pROC

---

# Estrutura Esperada

Coloque os arquivos na mesma pasta:

```text
ProjetoIA/
│
├── RandomForest.R
├── Heart_Attack_Data_Set.csv
```
---

# Instalação das Dependências

Abra o RStudio e execute:

```r
install.packages("caret")
install.packages("randomForest")
install.packages("ggplot2")
install.packages("pROC")
```

---

# Como Executar

## 1. Abrir o projeto

Abra o arquivo:

```text
RandomForest.R
```

no RStudio.

---

## 2. Definir diretório

Verifique se o dataset está na mesma pasta do script.

---

## 3. Executar

Você pode executar de duas formas:

### Executar linha por linha

Atalho:

```text
Ctrl + Enter
```

---

### Executar o script completo

Clique em:

```text
Source
```

ou:

```text
Source with Echo
```

---

# O Que o Projeto Faz

O código realiza:

- leitura do dataset
- análise inicial dos dados
- divisão treino/teste
- treinamento com Random Forest
- ajuste de hiperparâmetros
- geração de métricas
- matriz de confusão visual
- curva ROC
- cálculo de AUC
- importância das variáveis
- exportação automática dos gráficos

---

# Métricas Geradas

O projeto calcula:

- Accuracy
- Precision
- Recall
- F1-Score
- Kappa
- AUC

---

# Arquivos Gerados

Após executar, serão criados automaticamente:

```text
matriz_confusao.png
importancia_variaveis.png
curva_roc.png
```

---

# Dataset Utilizado

O dataset contém informações clínicas relacionadas a doenças cardíacas, incluindo:

- idade
- colesterol
- pressão arterial
- frequência cardíaca
- entre outros atributos médicos

---

# Objetivo

Treinar um modelo capaz de prever a presença de doença cardíaca com base em variáveis clínicas.

---

# Exemplo de Resultado

O modelo alcançou aproximadamente:

```text
AUC ≈ 0.84
```

Indicando bom desempenho preditivo.

---

# Autor
Filipe Silva da Fonseca e Grupo
---
Projeto acadêmico desenvolvido para estudo de Machine Learning utilizando Random Forest em R.
