# Stock Analysis Agent

![alt imagem de capa](./.github/wallpaper.png)

Este projeto é um sistema de análise de preços de ações que utiliza ferramentas de IA para buscar, analisar e gerar relatórios sobre tendências de mercado. Ele combina dados financeiros, notícias e análises aprofundadas para fornecer insights sobre ativos específicos.

## Funcionalidades

- **Fetch Stock Prices**: Utiliza a API do Yahoo Finance para buscar o histórico de preços de ações de um ano.
- **Analyze Market Trends**: Um agente de IA analisa os preços das ações e identifica tendências de alta, baixa ou estabilidade.
- **Summarize Market News**: Um agente especializado em notícias resume as informações mais relevantes sobre as ações solicitadas, incluindo um índice de medo/ganância.
- **Generate Reports**: Um analista sênior gera um boletim informativo detalhado com as análises de preços e notícias.

## Bibliotecas Utilizadas

- **yfinance**: Para obter dados históricos de preços de ações.
- **LangChain**: Para construção e gerenciamento dos agentes de IA.
- **Streamlit**: Para interface de usuário interativa.
- **OpenAI**: Para utilizar o modelo GPT-3.5-turbo na geração de análises e relatórios.
- **DuckDuckGoSearchResults**: Para buscar e sumarizar notícias de mercado.

## Instalação

1. Clone o repositório:

```
   https://github.com/Humberto08/stocksAgents.git
   cd stock-analysis-agent
```
2. Instale as dependências:

```
  pip install -r requirements.txt
```
3. Configure a chave da API da OpenAI no Streamlit:
```
  streamlit secrets set OPENAI_API_KEY "sua-api-key"
```

## Como Usar

1. Execute a aplicação:
```
  streamlit run app.py
```
2. Insira o ticket da ação no campo de pesquisa e clique em "Run Research".

3. Visualize os resultados da pesquisa, incluindo o relatório de tendências e o boletim informativo.

## Estrutura do Projeto

- app.py: Arquivo principal que executa o Streamlit e coordena os agentes.

- agents/: Contém a definição dos agentes e suas tarefas.

- tools/: Ferramentas integradas como a de busca de preços e análise de notícias.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Autores e colaboradores

- [@Humberto Luciano](https://www.github.com/Humberto)


<div id='contatos' align="center">
  <p align="center">Made with 💜 by Humberto Luciano</p>
  <div id="contatos" align="center">
    <a href="https://www.linkedin.com/in/humberto-luciano/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>