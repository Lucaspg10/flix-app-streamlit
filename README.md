[Read this in English](README.en.md)

# Flix App - Sistema de Gestão Cinematográfica 🎬
![Dashboard do Flix App](./images/dashboard.png)

Este projeto é uma aplicação Web completa desenvolvida para gerenciar um catálogo de filmes, atores e avaliações. Ele serve como a base arquitetural para o **SGE (Sistema de Gestão de Estoque)**

## 🚀 Tecnologias Utilizadas
* **Python** (Linguagem base)
* **Streamlit** (Interface Web)
* **Pandas** (Manipulação de dados)
* **Plotly** (Dashboards estatísticos)
* **Requests** (Consumo de API REST com JWT)

## 🏗️ Arquitetura
O projeto segue o padrão de **Separação de Preocupações (SoC)**, utilizando as camadas:
* **Pages**: Interface e componentes Streamlit.
* **Services**: Lógica de negócio e gerenciamento de estado (session_state).
* **Repositories**: Comunicação direta com a API.

## 🛠️ Como executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Execute o linter para garantir o padrão PEP8: `flake8 .`
3. Rode o app: `streamlit run app.py`

---
*Status: Finalizado (Base para o SGE da SEINFRA)* [2026-02-10]
