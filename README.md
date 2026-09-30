# Mini Projeto - Web Scraping de League of Legends

## 📌 Sobre o projeto

Este projeto foi desenvolvido como um mini projeto acadêmico, com o objetivo de aplicar na prática conceitos de Web Scraping utilizando Python.

Para o projeto, foi escolhida a League of Legends Wiki como fonte de dados. O programa acessa as páginas dos campeões, analisa o conteúdo HTML e realiza a extração automática de informações relevantes.

### utilizadas

- Python
- Requests
- Beautiful Soup

## 🎯 Objetivo

O objetivo do projeto é automatizar a coleta de informações sobre campeões de League of Legends.

O programa realiza requisições às páginas dos campeões, analisa o conteúdo HTML e extrai informações como:

- Nome;
- Título;
- Rota;
- Classe;
- Tags;
- Data de lançamento.

- A Utilidade Seria para: jogos Quiz, Builds, Conhecer melhor cada personagem.

Além disso, o programa permite consultar um campeão pelo nome, facilitando a visualização das informações coletadas.

💡 Possíveis aplicações

Os dados coletados podem ser utilizados como base para diferentes aplicações, como:

Quizzes sobre League of Legends;

Sistemas de consulta de campeões;

Estudos sobre os personagens do jogo;

Sistemas de recomendação de builds;

▶️ Como rodar

O projeto foi desenvolvido para ser executado no Google Colab, não sendo necessário instalar o Python ou configurar um ambiente local.

1. Acesse o projeto

Abra o arquivo:

LoL_Web_Scraping.ipynb

No GitHub, clique no botão Open in Colab localizado na parte superior do notebook.

2. Execute o notebook

No Google Colab:

Execute as células em ordem;

Aguarde a coleta automática da lista de campeões;

Digite o nome do campeão que deseja consultar;

O programa realizará a requisição à Wiki e exibirá as informações encontradas.

3. Dependências

As principais bibliotecas utilizadas no projeto são:

requests

beautifulsoup4

As dependências também estão disponíveis no arquivo requirements.txt.
