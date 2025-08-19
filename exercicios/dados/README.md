# Datasets – PPEQ-1040

Esta pasta reúne **conjuntos de dados** (datasets) para exercícios práticos da disciplina **PPEQ-1040 – Modelagem de Processos Baseada em Dados**.  
Os arquivos podem ser utilizados em atividades de análise exploratória, regressão, classificação e modelagem de processos.

---

## 📑 Lista de datasets

### 1. `water_potability.csv`
- **Descrição:** Dados de potabilidade da água com variáveis físico-químicas (pH, sólidos totais dissolvidos, condutividade, turbidez, etc.).
- **Tamanho:** ~3.200 amostras.
- **Aplicações:** classificação (água potável ou não), análise de correlação, pré-processamento de dados.

### 2. `wastewater_treatment.csv`
- **Descrição:** Dados de uma estação de tratamento de efluentes (ETE), incluindo parâmetros físico-químicos ao longo do processo.
- **Fonte:** UCI Machine Learning Repository.
- **Aplicações:** regressão multivariada, desenvolvimento de sensores virtuais, controle de processos.

### 3. `air_quality.csv`
- **Descrição:** Monitoramento da qualidade do ar em uma cidade, com variáveis como CO, NOx, O3 e temperatura.
- **Fonte:** UCI Machine Learning Repository.
- **Aplicações:** séries temporais, análise de poluição atmosférica, PCA.

### 4. `co2_emissions.csv`
- **Descrição:** Dados de emissões de CO2 de veículos em função de consumo de combustível e características do motor.
- **Fonte:** Kaggle.
- **Aplicações:** regressão linear/múltipla, análise estatística.

### 5. `energy_efficiency.csv`
- **Descrição:** Medidas de eficiência energética em edifícios (isolamento, área, orientação, etc.).
- **Fonte:** UCI Machine Learning Repository.
- **Aplicações:** regressão multivariada, PCA, otimização.

### 6. `chemical_process_yield.csv`
- **Descrição:** Dados experimentais de um processo químico, com variáveis de operação e rendimento do processo.
- **Fonte:** Kaggle.
- **Aplicações:** regressão não linear, otimização de condições experimentais.

---

## 🔧 Como utilizar
Exemplo em Python para carregar qualquer dataset desta pasta:

```python
import pandas as pd

# Exemplo: leitura do dataset de potabilidade da água
url = "https://raw.githubusercontent.com/juliosdutra/modelagem-processos-dados/main/exercicios/dados/water_potability.csv"
df = pd.read_csv(url)

print(df.shape)
print(df.head())

```
##  📌 Observações

* Os datasets foram escolhidos por sua relevância para a Engenharia Química e tamanho reduzido, facilitando o uso em aulas práticas.
* Sempre verificar se há valores ausentes ou inconsistentes antes de aplicar métodos de modelagem.
* As fontes originais (UCI, Kaggle, etc.) podem ser consultadas para descrições mais detalhadas.
