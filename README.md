# Sobre o Projeto: Análise de Tráfego Aéreo e Emissões de CO2
Olá!

Este é o projeto de análise de dados de tráfego aéreo e emissões de CO2, desenvolvido utilizando Python, PostgreSQL, Power BI e ferramentas de visualização como Matplotlib e Seaborn. O objetivo do projeto é estudar a relação entre a quantidade de voos e as emissões de CO2 por diferentes países e períodos.

**Ferramentas Utilizadas**

![Python](https://img.shields.io/badge/Python-00000F?style=for-the-badge&logo=python&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-00000F.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-00000F.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikitlearn](https://img.shields.io/badge/scikitlearn-00000F.svg?style=for-the-badge&logo=scikitlearn&logoColor=white)
[![POSTGRESQL](https://img.shields.io/badge/POSTGRES-00000F?style=for-the-badge&logo=POSTGRESQL&logoColor=white)]()
![Docker](https://img.shields.io/badge/docker-00000F.svg?style=for-the-badge&logo=docker&logoColor=white)
![PòwerBi](https://img.shields.io/badge/PowerBi-00000F.svg?style=for-the-badge&logoColor=white)

# Descrição do Projeto

O projeto realiza a análise de dois conjuntos de dados: o tráfego aéreo e as emissões de CO2 de diferentes países, de 2016 a 2024. Os dados foram processados para limpeza e correção de inconsistências, e em seguida armazenados em um banco de dados PostgreSQL para consultas e análises posteriores.

# Funcionalidades

**Limpeza e Preparação dos Dados:**

Os dados de tráfego aéreo e emissões de CO2 foram carregados e limpos, com valores nulos preenchidos e normalização dos nomes de países.

**Análise Temporal:**

Análises anuais e mensais foram realizadas para ambos os conjuntos de dados, permitindo a visualização de tendências ao longo do tempo.

# Integração dos Dados:
Foi realizado o merge entre os datasets de tráfego aéreo e emissões de CO2, corrigindo diferenças de nomenclaturas entre países como 'CZECHIA' e 'CZECH REPUBLIC'.

**Exportação para CSV:**

Após o tratamento e análise, os dados finais foram exportados para CSV para documentação e uso em relatórios futuros. 

**Banco de Dados:**

Utilizou-se o PostgreSQL para armazenamento dos dados, facilitando consultas e agregações complexas para relatórios.


**Visualização de Dados:**

Foram gerados gráficos para análise das emissões de CO2 e tráfego aéreo por ano e por mês, usando as bibliotecas Seaborn e Matplotlib. Alem disso, foi ultilizado PowerBi para fazer dashboards interativos para ter uma melhor compreensão e entendimento do dados.


# Visões e Análises

**Graficos anuais:**

- Total de Voos por Ano : Gráfico de linhas mostrando a variação do número de voos ao longo dos anos.

- Emissões de CO2 por Ano: Gráfico de linhas mostrando as emissões de CO2 por ano.

- Eficiência de CO2 por Voo por ano: Calculada a quantidade de CO2 emitida por voo para cada país e ano.



![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

**Graficos mensais/por territorio:**

- Total de Voos por Mês e por Pais: Análise mensal por pais para entender os picos de tráfego aéreo ao longo do ano.

- Total de Emissões por Mês e por Pais: Análise mensal por pais para entender os picos de emissão de CO2 ao longo do ano.

- Eficiênciade CO2 por Mês e por Pais :nálise mensal por pais para entender a eficiência de CO2 por voo ao longo do ano.


![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



