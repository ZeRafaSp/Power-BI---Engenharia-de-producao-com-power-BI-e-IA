# 🏭 Engenharia de Produção com Power BI e IA

## 📌 Sobre o Projeto

Este projeto foi desenvolvido utilizando **Microsoft Power BI**, explorando recursos de **Inteligência Artificial disponíveis na própria ferramenta**, com o objetivo de analisar dados de produção industrial, identificar possíveis anomalias e realizar previsões sobre a média de unidades produzidas ao longo do tempo.

O dashboard apresenta uma visão analítica da produção considerando diferentes períodos, turnos e faixas etárias dos funcionários, permitindo explorar o comportamento histórico dos dados, identificar tendências e gerar previsões para os anos seguintes.

Este projeto representa o **projeto final desenvolvido durante o curso de Power BI da Data Science Academy (DSA)**, consolidando conhecimentos de análise de dados, modelagem, visualização, DAX e utilização de recursos avançados do Power BI.

---

## 📊 Funcionalidades do Dashboard

O dashboard possui recursos para análise de:

- 🏭 Total de unidades produzidas ao longo do período;
- 📅 Análise por ano, trimestre, mês e período;
- 👥 Média de unidades produzidas por faixa etária dos funcionários;
- 🕐 Análise por turno de trabalho;
- 🚨 Detecção de possíveis anomalias na produção;
- 🔮 Previsão da média de produção para um horizonte de até 5 anos;
- 🎯 Filtros interativos por turno;
- 👤 Filtros por faixa etária;
- 📈 Análise de tendências da produção ao longo do tempo.

---

## 🤖 Inteligência Artificial e Análise Avançada

Um dos diferenciais deste projeto é a utilização de **recursos de Inteligência Artificial e análise avançada disponíveis nativamente no Power BI**.

Os recursos foram acessados diretamente pela área de **Visualizações** do Power BI, utilizando as funcionalidades disponíveis para análise de dados e séries temporais.

### 🚨 Detecção de Anomalias

O recurso de detecção de anomalias foi utilizado para identificar pontos que apresentam comportamento diferente do padrão observado na série histórica de produção.

No dashboard, essas possíveis anomalias são destacadas visualmente, facilitando a identificação de períodos que podem exigir uma análise mais detalhada.

### 🔮 Previsão

Também foi utilizado o recurso de previsão disponível no Power BI para estimar o comportamento futuro da média de unidades produzidas.

A análise apresenta uma projeção com horizonte de **5 anos**, permitindo comparar o comportamento histórico da produção com a tendência prevista para os períodos seguintes.

> **Importante:** neste projeto foram utilizados os recursos de IA e previsão disponibilizados pelo próprio Power BI. O objetivo foi demonstrar a aplicação prática dessas funcionalidades na análise de dados, e não desenvolver um modelo de Machine Learning do zero.

---

## 📈 Principais Análises

Com este dashboard é possível:

- Analisar a evolução da produção ao longo dos anos;
- Identificar tendências de crescimento ou redução da produção;
- Comparar a produção entre diferentes faixas etárias;
- Avaliar o comportamento da produção por turno;
- Identificar possíveis períodos com comportamento anômalo;
- Visualizar uma previsão da produção para os próximos anos;
- Comparar dados históricos com os valores previstos;
- Utilizar filtros para realizar análises mais específicas.

---

## 🗂️ Modelo de Dados

O modelo utilizado neste projeto é composto pela tabela **Produção**.

### Principais campos

- `Período`
- `Range Idade Funcionários`
- `Total Unidades Produzidas`
- `Turno`

### Medida utilizada

- `Média móvel da Soma de Total Unidades Produzidas`

A estrutura do modelo foi mantida de forma simples, utilizando a tabela de produção como fonte dos dados analisados pelo dashboard.

---

## 🛠️ Tecnologias e Recursos Utilizados

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Modelagem de Dados**
- **Visualizações Interativas**
- **Detecção de Anomalias**
- **Previsão de Séries Temporais**
- **Recursos de Inteligência Artificial do Power BI**
- **Análise de Dados**
- **Data Visualization**
- **Storytelling com Dados**

---

## 📷 Prévia do Dashboard

### Dashboard Principal

![Dashboard Principal](imagens/dashboard.png)

### Modelo de Dados

![Modelo de Dados](imagens/modelagem.png)

---

## 🎯 Competências Demonstradas

Este projeto demonstra conhecimentos em:

- Construção de dashboards interativos;
- Modelagem e organização de dados;
- Power Query;
- DAX;
- Análise exploratória de dados;
- Análise temporal;
- Identificação de tendências;
- Detecção de anomalias;
- Previsão de dados;
- Utilização de recursos de IA no Power BI;
- Storytelling com dados;
- Construção de indicadores;
- Visualização de dados;
- Análise aplicada ao contexto de produção industrial.

---

## 🎓 Formação

Projeto desenvolvido como parte da formação prática no curso de **Power BI da Data Science Academy (DSA)**.

Ao longo da formação foram trabalhados conceitos relacionados a:

- Business Intelligence;
- Power BI;
- Power Query;
- Tratamento e preparação de dados;
- Modelagem de dados;
- DAX;
- Visualização de dados;
- Análise exploratória;
- Construção de dashboards;
- Recursos avançados de análise no Power BI.

Este projeto representa a aplicação prática desses conhecimentos em uma análise voltada para o contexto de **produção industrial**.

---

## 📁 Estrutura do Repositório

```text
📂 Production-Analytics-PowerBI
│
├── 📊 Dashboard.pbix
├── 📄 README.md
│
└── 📂 imagens
    ├── dashboard.png
    └── modelagem.png


🚀 Como Visualizar
Faça o download do arquivo .pbix;
Instale o Power BI Desktop;
Abra o arquivo no Power BI Desktop;
Navegue pelo dashboard;
Utilize os filtros e interaja com as visualizações.

Observação: o projeto foi desenvolvido utilizando o Power BI Desktop.

##👨‍💻 **Autor**

José Rafael Santos Pereira

Desenvolvendo projetos práticos com:

Power BI | SQL | Python | Business Intelligence

GitHub:
https://github.com/ZeRafaSp/

LinkedIn:
https://www.linkedin.com/in/rafaelsantospereirarsp/
