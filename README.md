<div align="center">
  
  `Alchemists`
  
  <img src="https://github.com/user-attachments/assets/a7f74e09-9162-455e-8894-a9ec267155c6" width="300">
</div>
<hr>

# Análise dos Níveis de Obesidade

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

![GitHub](https://img.shields.io/github/license/atlantico-academy/equipe1-2024.1.svg) [![PyPI](https://img.shields.io/pypi/v/atlantico-academy-equipe1-2024.1.svg)](http://pypi.org/project/atlantico-academy-equipe1-2024.1/) 

**[Documentação](./docs/index.md)** | **[Dados](./docs/data.md)** | **[Execução](./docs/code.md)** | **[Insights](./docs/insight.md)**

## Contexto

A obesidade, distúrbio que envolve excesso de gordura corporal, é reconhecida como um problema de saúde pública pela OMS, sendo uma condição médica complexa e um dos principais desafios do século XXI. Ela está associada a várias doenças crônicas, como diabetes tipo 2, doenças cardíacas e hipertensão, além de impacto significativo na qualidade de vida. Estamos realizando essa análise para avaliar o conjunto de fatores que desencadeiam essa condição. 

## Justificativa

Com o aumento contínuo das taxas de obesidade em diversos países, faz-se necessário entender os fatores que contribuem para essa condição e assim desenvolver estratégias eficazes de prevenção e tratamento. 

## Resumo Gráfico

![image](https://github.com/user-attachments/assets/13e8f6f8-6b29-4cea-8458-73dbb4780d94)


## Desenvolvedores

[<img src="https://github.com/user-attachments/assets/640817fc-abb8-4c51-b26a-635485cb495d"  width="150" height="150">](https://github.com/dutradaphne) | [<img src="https://github.com/user-attachments/assets/f077c8d7-a41e-48e1-947a-0a0819428ca7" width="150" height="150">](https://github.com/IsabelleDays) | [<img src="https://github.com/user-attachments/assets/c54be732-877d-46c6-8448-217262ca27bb"  width="150" height="150">](https://github.com/PedroJoas) | [<img src="https://github.com/user-attachments/assets/83915461-dafb-493d-9ffd-d4a834eabb4f"  width="150" height="150">](https://github.com/simires) | [<img src="https://github.com/user-attachments/assets/8d25120f-c0fb-4928-8eed-eca9bcccf8ea"  width="150" height="150">](https://github.com/vincenzofadda) | [<img src="https://github.com/user-attachments/assets/17c9375d-b31a-4063-a5f1-6abf2960030b"  width="150" height="150">](https://github.com/mevivi) 
--- | --- | --- | --- | --- | --- 
[Daffny Dutra](https://github.com/dutradaphne) | [Isabelle Dias](https://github.com/IsabelleDays) |  [Pedro Joás](https://github.com/PedroJoas) | [Simires de Souza](https://github.com/simires) | [Vicenzzo Fadda](https://github.com/vincenzofadda) | [Vitoria Rosa](https://github.com/mevivi) 

### Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
