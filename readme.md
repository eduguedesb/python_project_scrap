Este código realiza web scraping para extrair todos os links (URLs) de uma página da web e os salva em um arquivo de texto. Ele utiliza as bibliotecas Requests e BeautifulSoup para fazer requisições HTTP e processar o HTML da página.

Principais Funcionalidades:

Requisição HTTP: Faz uma requisição à URL fornecida pelo usuário e obtém o conteúdo HTML da página.
Extração de URLs: Usa o BeautifulSoup para analisar o HTML e extrair todas as URLs presentes nas tags <a> (links).
Tratamento de erros: Inclui tratamento para erros comuns, como falhas de conexão, tempo limite e erros de solicitação HTTP.
Armazenamento de URLs: Salva todas as URLs capturadas em um arquivo de texto (urls.txt), facilitando o acesso posterior.

Como Funciona:

O código solicita ao usuário que insira a URL da página da web que deseja fazer scraping.
A função extrair_urls faz uma requisição à URL usando um cabeçalho de "User-Agent" customizado para simular um navegador real.
Se a requisição for bem-sucedida, o código usa o BeautifulSoup para localizar todas as tags <a> e extrair os links das páginas.
As URLs extraídas são salvas em um arquivo de texto chamado urls.txt.
