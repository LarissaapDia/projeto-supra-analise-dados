# Análise do Tempo Porta-Balão no Projeto SUPRA

## Visão geral
Este projeto apresenta uma análise exploratória e preditiva sobre o fluxo assistencial de pacientes com suspeita de IAMCSST confirmados no contexto do Projeto SUPRA, com foco nos tempos críticos do atendimento e no indicador Tempo Porta-Balão (TPB).

## Objetivo
Investigar o comportamento das principais variáveis temporais do fluxo assistencial, identificar padrões de atraso e explorar fatores associados ao não atingimento da meta de TPB total menor que 120 minutos.

## Período analisado
2023 a 2025

## Dados analisados
O conjunto de dados utilizado neste projeto contém informações anonimizadas e agregadas sobre pacientes com suspeita de IAMCSST confirmados.

As variáveis principais incluem:
- TPE
- Tempo na unidade de origem
- Tempo de transporte
- TPB hospitalar
- TPB total

## Etapas do projeto
- Descrição e inspeção dos dados
- Estatísticas descritivas
- Análise exploratória
- Visualização dos tempos do fluxo
- Avaliação do atingimento da meta de TPB < 120 min
- Modelagem preditiva com regressão logística
- Interpretação dos resultados

## Principais insights
- Identificação de variáveis com maior associação ao atraso no TPB total
- Compreensão de etapas do fluxo com maior impacto no tempo final
- Apoio à tomada de decisão orientada por dados em saúde

## Tecnologias utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estrutura do projeto
```text
analise-iamcsst-tpb/
├── data/
├── notebooks/
│   └── analise_projeto_SUPRA.ipynb
├── README.md
├── requirements.txt
└── .gitignore


##Observação sobre os dados

O dataset original não foi disponibilizado neste repositório por motivos de privacidade, sigilo institucional e governança de dados.

Autora

Larissa Dias