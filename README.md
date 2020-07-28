# Labenu | Desenvolvimento Web Full Stack

<p align="center">
  <img src="https://user-images.githubusercontent.com/59856574/86274338-e7bbd280-bba7-11ea-9b0f-312418c0c364.png"/>
</p>

## Projeto 4eddit front-end

:dash: [Deploy da aplicação](http://flat-limit.surge.sh/)

<br>

[Documentação da API consumida no projeto](https://documenter.getpostman.com/view/674905/SzYXXKEE?version=latest#08adf102-4d87-4f70-9dc3-b3c321b29739)

<p align="center">
  <img width="300px" src="https://i.imgur.com/GnNdSlH.png"/>
</p>

#### Neste projeto trabalhamos na reprodução de um modelo simplificado de funcionamento e consumo de uma API que se assemelha a aplicação do Reddit, onde posts podem receber <i>likes</i> e <i>unlikes</i>


<p align="center">
  <img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=redux&message=library&color=purple&style=for-the-badge&logo=REDUX"/>
  <img src="https://img.shields.io/static/v1?label=javascript&message=language&color=yellow&style=for-the-badge&logo=JAVASCRIPT"/>
  <img src="https://img.shields.io/static/v1?label=typescript&message=language&color=blue&style=for-the-badge&logo=TYPESCRIPT"/>
  <img src="https://img.shields.io/static/v1?label=styled-component&message=library&color=blue&style=for-the-badge&logo=STYLED-COMPONENTS"/>
   <img src="https://img.shields.io/static/v1?label=material-ui&message=library&color=blue&style=for-the-badge&logo=MATERIAL-UI"/>
</p>

> Status do Projeto: Completo

## Resumo das funcionalidades:

<p align="justify"> 
Nesse projeto, integramos uma aplicação front-end com uma API, conectando o front com endpoints que possibilitam que:
- O usuário se cadastre, acesse o feed de sua home logo após concluir o cadastro (com sucesso)
- Crie e publique posts com conteúdos de texto, assim como demais usuários de outros fronts integrados na mesma API
- Comente nos posts renderizados no feed
- Dê likes e dislikes nos posts e nos comentários dos posts
Acrescentamos outros elementos visuais que ficaram meramente ilustrativos, como um input de busca e o ícone de salvar posts. 
Com o prazo de 4 dias para o projeto, preferimos não completar implementações lógicas mais complexas para nós naquele momento.
</p>

## Descrição do Projeto 

<p align="justify"> 
 Essa semana, vocês irão implementar uma rede social! Já fizemos vários protótipos de redes sociais, mas nenhuma delas realmente funcional. A ideia agora é fazer uma rede real, com cadastro, login, posts, likes e comentários. Para isso, iremos nos basear no reddit.com.
</p>

### Página de Login
<p align="center"><img src="https://i.imgur.com/X8MccTG.png"/><br></p>
<p align="justify">
  A página de login possui dois campos de texto: email e senha. O comportamento será o mesmo da página de login feita semana passada. Ao fazer o login, o usuário deverá ser redirecionado para a página de feed.
  A página possui também um botão "Cadastrar", que leva o usuário para a página de cadastro.
</p>

### Página de Cadastro
<p align="center"><img src="https://i.imgur.com/hMIxUHe.png"/></p>
<p align="justify">
  A página de cadastro possui 3 campos: nome de usuário, email e senha. O endpoint de cadastro retornará as mesmas informações do endpoint de login. Portanto, após cadastrar, o usuário deverá ser redirecionado para a página de feed, já estando logado (ou seja, com o token salvo no LocalStorage)  .
</p>

### Página de feed (lista de posts)
<p align="center"><img src="https://i.imgur.com/GNNYwih.png"/></p>
<p align="justify">
 A página de feed deverá mostrar todos os posts, além de um formulário para a criação de post. O formulário possui apenas o campo de texto. Cada post mostrará o nome de usuário que postou, o texto do post, o número de votos (positivo ou negativo) e o número de comentários. Caso o usuário tenha votado positiva ou negativamente, isso deverá estar indicado. Todas essa informações serão fornecidas pela API.
  Quando o usuário clicar em um post, ele deverá ser redirecionado para a página do respectivo post.
  Quando um usuário clicar em votar (positiva ou negativamente), uma requisição deverá ser feita indicando a "direção" do voto. Um voto positivo é indicado com o número ```1```. Um voto negativo é indicado com o número ```-1```. Para remover um voto, a direção deve ser ```0```.
  Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.
</p>

### Página de post
<p align="center"><img src="https://i.imgur.com/A1YCI3d.png"/></p>
 <p align="justify">
  A página de um post mostrará o mesmo card de post da página de feed, com o usuário, texto, curtidas e número de comentários. Abaixo, terá um formulário para criação de comentários e os cards de comentários. A estrutura é muito similar à do post, mas comentários não possuem outros comentários dentro deles. A lógica de votos é a mesma do post.
  Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.
</p>


## Desenvolvido Por :octocat:

| [<img src="https://i.imgur.com/s55W74x.jpg" width=115><br><sub>João Pedro Fonseca Achkar </sub>](https://www.linkedin.com/in/joaopfa/) | 
| :---: |
&
| [<img src="https://media-exp1.licdn.com/dms/image/C4D03AQFffOc1nWKqGA/profile-displayphoto-shrink_800_800/0?e=1601510400&v=beta&t=rh0YwZkZOTQ1oDkAcxD4XImKg8aYW3ypUCwJRxYTlmw" width=115><br><sub>Igor Deleposti </sub>](https://www.linkedin.com/in/igordelesposti/) | 


## Licença 

[MIT License](https://github.com/nauaramelo/spotenu-front/blob/master/LICENSE)

