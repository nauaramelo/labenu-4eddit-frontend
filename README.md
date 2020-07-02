# Labenu | Desenvolvimento Web Full Stack


<p align="center">
  <img src="https://user-images.githubusercontent.com/59856574/86274338-e7bbd280-bba7-11ea-9b0f-312418c0c364.png"/>
</p>

## Projeto 4eddit 

<p align="center">
  <img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=javascript&message=language&color=yellow&style=for-the-badge&logo=JAVASCRIPT"/>
  <img src="https://img.shields.io/static/v1?label=redux&message=library&color=purple&style=for-the-badge&logo=REDUX"/>
  <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
  <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
</p>

> Status do Projeto: Em desenvolvimento :warning: 


## Descrição do projeto 

Vocês irão implementar uma rede social! Já fizemos vários protótipos de redes sociais, mas nenhuma delas realmente funcional. A ideia agora é fazer uma rede real, com cadastro, login, posts, likes e comentários. Para isso, iremos nos basear no **[reddit.com](https://reddit.com).**

A rede social terá 4 páginas:

### 1. Página de login

![1](https://user-images.githubusercontent.com/3521896/77802249-3ada3280-7059-11ea-9da7-5762c6daf97d.png)

A página de login possui dois campos de texto: email e senha. O comportamento será o mesmo da página de login feita semana passada. Ao fazer o login, o usuário deverá ser redirecionado para a página de feed.

A página possui também um botão "Cadastrar", que leva o usuário para a página de cadastro.

### 2. Página de cadastro

![2](https://user-images.githubusercontent.com/3521896/77802253-3ca3f600-7059-11ea-8bc9-e43db687e62c.png)

A página de cadastro possui 3 campos: nome de usuário, email e senha. O endpoint de cadastro retornará as mesmas informações do endpoint de login. Portanto, após cadastrar, o usuário deverá ser redirecionado para a página de feed, já estando logado (ou seja, com o token salvo no LocalStorage).

### 3. Página de feed (lista de posts)

![3](https://user-images.githubusercontent.com/3521896/77802257-3e6db980-7059-11ea-9978-cc4612e444a1.png)

A página de feed deverá mostrar todos os posts, além de um formulário para a criação de post. O formulário possui apenas o campo de texto. Cada post mostrará o nome de usuário que postou, o texto do post, o número de votos (positivo ou negativo) e o número de comentários. Caso o usuário tenha votado positiva ou negativamente, isso deverá estar indicado. Todas essa informações serão fornecidas pela API.

Quando o usuário clicar em um post, ele deverá ser redirecionado para a página do respectivo post. 

Quando um usuário clicar em votar (positiva ou negativamente), uma requisição deverá ser feita indicando a "direção" do voto. Um voto positivo é indicado com o número `1`. Um voto negativo é indicado com o número `-1`. Para remover um voto, a direção deve ser `0`.

Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.

### 4. Página de post

![4](https://user-images.githubusercontent.com/3521896/77802261-40377d00-7059-11ea-8f65-2b305bf5e6f8.png)

A página de um post mostrará o mesmo card de post da página de feed, com o usuário, texto, curtidas e número de comentários. Abaixo, terá um formulário para criação de comentários e os cards de comentários. A estrutura é muito similar à do post, mas comentários não possuem outros comentários dentro deles. A lógica de votos é a mesma do post.

Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.


## Pré-requisitos

:warning: [React](https://pt-br.reactjs.org/)

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto: 

```
git clone https://github.com/nauaramelo/labenu-4eddit-frontend.git
```
Entre no projeto e instale as dependências através do comando:
```
npm install
```
Por último, suba a aplicação: 
```
npm start
```

## Linguagens, dependencias e libs utilizadas :books:

- [React](https://pt-br.reactjs.org/)
- [Redux](https://redux.js.org/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://alligator.io/react/axios-react/)
- [Material ui](https://material-ui.com/pt/)

## Desenvolvido Por: :octocat:

| [<img src="https://user-images.githubusercontent.com/59856574/86283681-d11d7780-bbb7-11ea-90a5-9312ee67cdec.jpg" width=115><br><sub>Nauara Melo</sub>](https://www.linkedin.com/in/nauara-melo-mayer-464a82135/) | 
| :---: |

## Licença 

[MIT License](https://opensource.org/licenses/MIT)

Copyright :copyright: 2020 - 4eddit
