# Desafio_beAnalytic
Projeto desafio par empresa beAnalytic

Desenvolvimento do projeto "Acompanhamento de promocoes Steam" com o intuito de extrair e manipular dados utilizando a biblioteca PANDAS e carregar numa Google sheet.

**Todo projeto foi desenvolvido com a linguagem de programação Python.**

## ✒️Autor
- [Diogo Moura](https://github.com/HyogoMoura)

## 📋Enunciado do Projeto

Descrição
-  os notebook contém a descrição do projeto prático para extracao de dados da SteamDB: Neste projeto aplico as técnicas de extracao usando API e alternativamente usando o selenium.

Objetivo
- Realize a extração das informações que conseguir da base de dados listada no website: https://steamdb.info/sales/

Dados
- Os dados vao ser extraidos diretamente pela API ou via web scraping.
- Obs web scraping com selenium so funcionando em IDE local.

Organização e entregáveis:
- Armazene estes dados no Google BigQuery.
- Exportar ou conecte esses dados em um Google Sheets.

Critérios de avaliação
**A avaliação será feita com base nos artefatos entregues e na sua apresentação.**

Entregáveis
- Notebook com análise exploratória de dados;
- Dataset bronze Google Sheets;

Critérios:
- Análise (O nível de exploração dos dados, quantidade de bases e variáveis);
- Reprodutibilidade (O código será executado e o resultados precisam ser reproduzidos);

## 📋 Descrição do Projeto

**1) Extração de Dados:**
- [SteamSpy](https://steamspy.com/api.php))
- [SteamDB](https://steamdb.info/sales/)

**2) Manipulação de Dados:** 
- Formatacao das tabelas e indices;
- limpeza dos dados;
- Verificação e conversão dos tipos de dados de cada coluna;
- Merge de DataFrames;

## Demonstração
<p align="center">
  <img src="./_captures/Demonstracao.gif">
</p>

## 📋  Pré-requisitos
- Ter instalado o **[Python](https://www.python.org/)**;
- Ter instalado todas as bibliotecas Python listadas ao decorrer desse Readme;
- Ter instalado uma IDE de sua preferencia:
    - **[Visual Studio Code](https://code.visualstudio.com/)**, por exemplo.
    - **[Google BigQuery_Notebook](https://colab.research.google.com/notebook)** (Não é necessário instalação).

## ⚙️ Executar o projeto:
- Fazer o clone do repositório do projeto [Projeto_Queimadas_M3](https://github.com/HyogoMoura/Desafio_beAnalytic);
- selecionar um dos notebooks a escolha;
- Selecionar a opção "Run All" para iniciar todas as funções;
- Pronto! Veja toda extracao e manipulacao.

## 🧾 Bibliotecas Python utilizadas
Clique sobre o link para instalar cada biblioteca utilizada.

- [Pandas](https://pypi.org/project/pandas/):
`import pandas as pd`

- [Numpy](https://numpy.org/)
`import numpy as np`

- [Selenium](https://www.selenium.dev/documentation/webdriver/)
`from selenium import webdriver

-[Requests](https://pypi.org/project/requests/)
`import requests

## 🛠️ Tecnologias Utilizadas
Python

* [Visual Studio Code](https://code.visualstudio.com/) - IDE
* [BigQueryNotebook](https://cloud.google.com/bigquery/docs/create-notebooks?hl=pt-br)
* [Python](https://www.python.org/) - Linguagem de Programação

## 📈 Melhorias futuras

- Automacao de coleta d+1
- Enriquecimento de tabela

## Agradecimento
- Daniel Luz
- Nara GuimarãesVer

