# Web Scraper - Kabum!

Este web scraper tem como objetivo extrair informações de preço e descrições de produtos do site [Kabum!](https://www.kabum.com.br). Os dados são exportados para um arquivo .CSV, facilitando a análise posterior.

## Bibliotecas e dependências

- Python 3
- Selenium 3.141.0 e *geckodriver*
- BeautifulSoup 4.9.3 com *requests 2.2* e *lxml*
- Pandas 1.1.4

## Atributos extraídos

Os atributos de cada produto foram deliberadamente selecionados:

- Título do anúncio
- Preço à vista
- Preço à prazo
- Avaliação (número de estrelas)
- Quantidade de avaliações recebidas