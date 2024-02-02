# Spotify Imersão
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/eomarkmano/spotify-imersao/blob/main/LICENSE)

# Sobre
*Spotify Imersão* se trata de uma aplicação para aprendizagem com foco em rever fundamentos e testar o uso de novas tecnologias/ferramentas de desenvolvimento front-end para aprimoramento.

O projeto foi idealizado em um evento chamado *"Imersão Front-End"* da [Alura](https://www.alura.com.br) e teve sua construção realizada em conjunto a partir das aulas. A ideia parte da reprodução de um Layout moderno de HomePage + adicional uso da barra de pesquisa, tendo como referência o famoso streaming de músicas: Spotify.
## Layout Web
![Homepage_1](https://github.com/eomarkmano/spotify-imersao/blob/main/src/assets/git%20resources/Homepage_1.png)

![Searchbar_1](https://github.com/eomarkmano/spotify-imersao/blob/main/src/assets/git%20resources/Searchbar_1.png)

# Tecnologias utilizadas
## Front-end
- HTML / CSS / JavaScript + Node.JS

## Back-end + Componentes externos
- *"Fake API"* with *JSON*
- Component: *JSON* Server

# Como executar o Projeto
> [!IMPORTANT]
> ### Pré-requisitos 
> - Node.JS + NPM resources (for *JSON* Server)
> ### Downloads e Comandos
> - Node.JS: https://nodejs.org/en/download
> - NPM resources: 
```bash
# No terminal:

cd api-artists
npm install -g json-server@0.17.4 

# Após instalação, zerar terminal e aplicar novo comando:

json-server --watch api-artists/artists.json --port 3000

## Obs: a Porta pode ser qualquer valor.
```

# Features
>[!NOTE]
> ### Biblioteca de Ícones e Conjuntos
> - Para auxílio com ícones específicos e demais itens na criação de botões e design geral, foi utilizado a biblioteca gratuita disponibilizada pela [Font Awesome](https://fontawesome.com).
> ### Barra de Pesquisa
> - Processo de busca por enquanto direcionado apenas para alguns artistas, criado a partir de funções definidas para chamar a *"Fake API" (JSON)* e carregar as informações conforme `input` de caracteres. 
> * Obs: Para tornar a busca funcional, é necessário seguir comando: `json-server` (Informações referenciadas em [***"Downloads e Comandos"***]().

**Pesquisa:** 

![Searchbar_2](https://github.com/eomarkmano/spotify-imersao/blob/main/src/assets/git%20resources/Searchbar_2.png) 

**Regra sendo aplicada no input:**

![Searchbar_monitor_1](https://github.com/eomarkmano/spotify-imersao/blob/main/src/assets/git%20resources/Searchbar_monitor_1.png)

# Autor

| [<img src="https://github.com/eomarkmano/spotify-imersao/assets/80011549/139bb173-03cf-464f-85d9-8535c4aa93ad" alt="profile_pic" width=75><br>***Marcos Oliveira***](https://github.com/eomarkmano) | 
| :---:

**LinkedIn:** https://www.linkedin.com/in/eomarkmano/

**E-mail:** marlitos38@gmail.com

# Agradecimentos

Em especial: [Alura](https://www.alura.com.br), responsável por apresentar a Imersão Front-end e por conduzir o projeto com dinamismo e cuidado.

**E OBRIGADO A VOCÊ!** Que chegou neste projeto 😄👊💻 
