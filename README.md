# Teste Simbiox: Front-End Developer
Desenvolver uma aplicação HTML5

## Instruções
- Faça um fork desse projeto para a sua conta pessoal do GitHub.
- Siga as especificações abaixo.
- Crie um README com as instruções para compilar, testar e rodar o projeto.
- O link do repositório deverá ser enviado para o e-mail
douglas.riu@simbiox.com.br com o título **Teste FrontEnd Developer**

## Especificações tecnicas
- Utilizar diretrizes do
[Google Material Design](https://www.google.com/design/spec/material-design/introduction.html)
- Utilizar a [OMDb API](http://www.omdbapi.com)
- Mobile first e responsivo
- Usar framework JS [Vue.JS](https://vuejs.org/) ou
[SharePoint framework](https://github.com/SharePoint/sp-dev-docs)
- Cores livres, layout livre, imagens livres

## Especificações funcionais
### Tela Inicial
Essa tela terá um formulário de busca posicionado no meio da tela com
campo de texto com placeholder "Procure seu filme" e um botão "Buscar".
Essa busca deverá chamar a url http://www.omdbapi.com/?s={nome_do_filme}.

Ao fazer a busca, o formulário deve ser movido para o topo da tela usando
css animate e mostrar a lista de filmes com os campos do retorno da chamada
(Título, Ano, Tipo, imdbID, Poster). O campo de busca deverá ter validação.

A lista de filmes deve mostrar apenas o poster do filme e um botão para ver
o detalhe do filme. Deve mostrar apenas os 6 primeiros resultados e deve
possuir paginação infinita mostrando de 6 em 6 resultados.

### Tela de detalhes
A partir do imdbID retornado na outra chamada, deve ser feito uma chamada
para http://www.omdbapi.com/?i={imbd_id}.

A partir desse retorno, deve-se montar uma tela onde apareçam as informações
Title, Year, Rated, Genre, Director, Writer, Actors, Plot, Language, Country, Awards, Poster, Type.
Essa tela deve ter um botão para voltar para resultados da busca.

## Plus

- Utilizar o proprio ambiente do SharePoint
[Dev Program](https://profile.microsoft.com/RegSysProfileCenter/wizardnp.aspx?wizid=14b845d0-938c-45af-b061-f798fbb4d170&lcid=1033)

    *O dev program é um meio de utilizar o sharepoint de graça*

    *Caso utilize o ambiente sharepoint crie um estrutura de
    lista com as mesmas propriedades do [OMDb API](http://www.omdbapi.com)*

- Utilizar o
[PnP-JS-Core](https://github.com/SharePoint/PnP-JS-Core) para comunicação com as apis
do sharepoint caso queira utilizar o ambiente SharePoint

- Testes automatizados

## O que será avaliado?
- Organização do projeto
- Lógica do código
- Uso do Git