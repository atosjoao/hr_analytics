# hr_analytics

# Análise de Dados na área de RH.

O Projeto tem como objetivo realizar uma análise descritiva de dados sobre colaboradores de uma Empresa.
O dataset foi retirado do Kaggle, através do link: https://www.kaggle.com/datasets/kmldas/hr-employee-data-descriptive-analytics/data.

# Case: Avaliação de Performance das Métricas de Satisfação do Trabalhador

💡 **Contexto** <br>
A Empresa possui algumas avaliações de satisfação de cada colaborador, bem como a quantificação das suas horas trabalhadas, projetos em que está participando ou se já foi vítima de algum acidente de trabalho, todas essas informações, estão contidas em uma planilha, em excel. O setor de RH solicitou uma análise desses dados, em formato de Jupyter Notebook ou em Dashboard, para que sejam capaz de identificar tendências e padrões de cada setor, afim de criar medidas de controle das métricas de satisfação.

## 1. Objetivo

Avaliar a performance dos principais indicadores de People Analytics, para auxiliar o setor de RH a tomar as melhores decisões para os colaboradores da empresa.

## 2. Metodologia

Para o relatório no Jupyter Notebook, a metodologia adotada será a de criar perguntas de negócios para entender, inicialmente, qual o cenário acerca dos resultados do dataset. Para responder estas perguntas, será utilizada estatística descritiva para sumarização dos dados, como o uso de medidas de centralidade (média, mediana e moda), medidas de dispersão (desvio padrão e coeficiente de variância) e medidas de formato, (simetria e curtose). 

Para o Dashboard, serão utilizadas técnicas de storylelling, para desenvolver uma narrativa visual que torne mais intuitivo o processo de análise dos dados. Essa narrativa auxiliará não apenas na disposição geográfica dos elementos, mas também, em quais elementos e métricas deverão ser priorizados, já que não há espaço suficiente para alocar para todos os cálculos e análises.

## 3. Entregáveis

1. Relatório no Jupyter Notebook.
2. Dashboard no Looker Studio.

## 4. Ferramentas

1. Python - Jupyter Notebook
2. Looker Studio
3. Estatística Descritiva
4. Storytelling

## 5. Base de Dados

A base de dados possui as seguintes características principais:

### 5.1 Colunas

- **Emp_Id:** Identificação do empregado
- **satisfaction_level:** Nível de satisfação (float)
- **last_evaluation:** Última avaliação (float)
- **number_project:** Número de projetos (int)
- **average_montly_hours:** Média de horas mensais trabalhadas (int)
- **time_spend_company:** Tempo de empresa em anos (int)
- **Work_accident:** Acidente de trabalho (int, 0 ou 1)
- **left:** Se o empregado deixou a empresa (int, 0 ou 1)
- **promotion_last_5years:** Promoção nos últimos 5 anos (int, 0 ou 1)
- **Department:** Departamento do empregado (category)
- **salary:** Faixa salarial (category)

# 6. Considerações
Para mim, este projeto não é, apenas, um meio de provar minhas habilidades, mas também, através do conhecimento de uma nova área, evoluir como analista. Através de novas perspectivas, abordagens e objetivos, construir uma maior maturidade analítica, sempre tendo em vista responder perguntas de negócios e propor soluções e insights para agregar valor a empresa.
