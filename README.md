# Análise do Tempo Porta-Balão (TPB) – Projeto SUPRA

## Contexto
Este projeto analisa o fluxo assistencial de pacientes com suspeita de IAM com supra de ST (IAMCSST) no contexto do Projeto SUPRA, com foco no indicador crítico **Tempo Porta-Balão (TPB)**.

O TPB é um dos principais indicadores de qualidade no atendimento cardiovascular, com meta recomendada de **≤ 120 minutos**.

---

## Objetivo
Identificar fatores associados ao atraso no TPB e compreender em quais etapas do fluxo assistencial ocorrem os maiores gargalos.

---

## Dados
- Período: 2023–2025  
- Casos: Pacientes com IAMCSST confirmados  
- Variáveis principais:
  - Tempo Porta-ECG (TPE)
  - Tempo na unidade de origem
  - Tempo de transporte
  - TPB hospitalar
  - TPB total

> ⚠️ Os dados não estão disponíveis publicamente por questões de privacidade e governança.

---

## Metodologia

### 1. Análise exploratória
- Estatísticas descritivas
- Distribuição dos tempos
- Identificação de outliers

### 2. Avaliação de desempenho
- Percentual de casos dentro da meta (TPB < 120 min)
- Análise por etapa do fluxo

### 3. Modelagem preditiva
- Regressão logística para prever atraso no TPB
- Identificação das variáveis mais relevantes

---

## Principais insights

- O atraso no TPB está mais associado a etapas pré-hospitalares
- Variáveis de transporte e tempo na origem têm maior impacto
- Existe variabilidade significativa entre unidades de origem

---

## Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Estrutura do projeto
projeto-supra-analise-dados/
├── data/ # não versionado
├── notebooks/
│ └── analise_projeto_SUPRA.ipynb
├── README.md
├── requirements.txt
└── .gitignore


---

## Aplicação prática

Este tipo de análise pode ser utilizado para:

- Redução de tempo de atendimento em redes de urgência
- Monitoramento de indicadores críticos
- Apoio à tomada de decisão baseada em dados na saúde

---

## Autora
Larissa Dias  