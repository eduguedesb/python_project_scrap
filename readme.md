# Visão Geral:
Este script realiza web scraping para extrair todos os links (URLs) de uma página da web e os salva em um arquivo texto. Ele utiliza as bibliotecas Requests e BeautifulSoup para fazer requisições HTTP e processar o HTML da página.

# Funcionamento:
O código solicita ao usuário que insira a URL da página da web que deseja fazer scraping.
<br>
A função extrair_urls faz uma requisição à URL usando um cabeçalho de "User-Agent" customizado para simular um navegador real.
<br>
Se a requisição for bem-sucedida, o código usa o BeautifulSoup para localizar todas as tags <a> e extrair os links das páginas.
<br>
As URLs extraídas são salvas em um arquivo texto chamado urls.txt.

# Dependências:
Dependências listadas no arquivo "requirements.txt".

# Como Usar:
Execute o script com o seguinte comando: py scrap.py ou python scrap.py.
