# Datasets – PPEQ-1040

Esta pasta reúne **conjuntos de dados** (datasets) para exercícios práticos da disciplina **PPEQ-1040 – Modelagem de Processos Baseada em Dados**.  
Os arquivos podem ser utilizados em atividades de análise exploratória, regressão, classificação e modelagem de processos.

---

## 📑 Lista de datasets

### 1. [water_potability.csv](https://raw.githubusercontent.com/juliosdutra/modelagem-processos-dados/main/exercicios/dados/water_potability.csv)
- **Descrição:** Dados de potabilidade da água com variáveis físico-químicas (pH, sólidos dissolvidos, condutividade, turbidez, etc.).
- **Aplicações:** classificação (água potável ou não), análise de correlação, pré-processamento de dados.

### 2. [wastewater_treatment.csv](https://archive.ics.uci.edu/ml/datasets/Wastewater+Treatment+Plant)
- **Descrição:** Dados de uma estação de tratamento de efluentes (ETE), com parâmetros físico-químicos.
- **Aplicações:** regressão multivariada, sensores virtuais, controle de processos.

### 3. [air_quality.csv](https://archive.ics.uci.edu/ml/datasets/Air+Quality)
- **Descrição:** Monitoramento da qualidade do ar (CO, NOx, O3, temperatura, etc.).
- **Aplicações:** séries temporais, análise de poluição atmosférica, PCA.

### 4. [co2_emissions.csv](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)
- **Descrição:** Emissões de CO2 de veículos em função de consumo de combustível e características do motor.
- **Aplicações:** regressão linear/múltipla, análise estatística.

### 5. [energy_efficiency.csv](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency)
- **Descrição:** Eficiência energética de edifícios (isolamento, área, orientação, etc.).
- **Aplicações:** regressão multivariada, PCA, otimização.

### 6. [chemical_process_yield.csv](https://www.kaggle.com/datasets/shivamb/chemical-process-yield)
- **Descrição:** Dados experimentais de processo químico, com variáveis de operação e rendimento.
- **Aplicações:** regressão não linear, otimização de condições experimentais.

OBS: https://archive.ics.uci.edu/datasets
---

## 🔧 Como utilizar
Exemplo em Python para carregar qualquer dataset desta pasta:

```python
import pandas as pd

# Exemplo: leitura do dataset de potabilidade da água
url = "https://raw.githubusercontent.com/juliosdutra/modelagem-processos-dados/main/dados/water_potability.csv"
df = pd.read_csv(url)

print(df.shape)
print(df.head())

```
##  📌 Observações

* Os datasets foram escolhidos por sua relevância para a Engenharia Química e tamanho reduzido, facilitando o uso em aulas práticas.
* Sempre verificar se há valores ausentes ou inconsistentes antes de aplicar métodos de modelagem.
* As fontes originais (UCI, Kaggle, etc.) podem ser consultadas para descrições mais detalhadas.
