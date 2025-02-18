# Web Scraping com BeautifulSoup

Este repositório contém um projeto de aprendizado sobre web scraping utilizando a biblioteca **BeautifulSoup**. O código foi desenvolvido no Google Colab e explora diferentes métodos para extrair informações de páginas web.

## 📌 Funcionalidades

- **Carregamento de páginas web**: Uso da biblioteca `requests` para obter o conteúdo HTML.
- **Navegação e busca no HTML**:
  - `find()` e `find_all()` para localizar elementos específicos.
  - `select()` para seleção baseada em CSS.
- **Extração de informações**:
  - Coleta de links de redes sociais.
  - Extração de dados de tabelas e conversão para DataFrame com `pandas`.
  - Busca por padrões em textos utilizando expressões regulares (`re`).
- **Manipulação de imagens**: Download de imagens hospedadas em uma página web.

## 🛠 Tecnologias Utilizadas

- **Python**
- **BeautifulSoup** (para parsing de HTML)
- **Requests** (para requisições HTTP)
- **Pandas** (para manipulação de tabelas)
- **Regex (`re`)** (para busca de padrões em textos)

## 📂 Estrutura do Projeto

- `web-scraping-test.ipynb` → Notebook do Google Colab com todo o código e anotações.
