# Teste SimbioX: Front-End Developer
Desenvolver uma aplicação para testar os 
conhecimentos Front-End com HTML, CSS e JavaScript, 
além de lógica de programação, organização e semântica.

## Especificações tecnicas
- Utilizar uma lib como Bootstrap, Materialize ou alguma outra de sua preferência
- Utilizar a API [CartolaFC API](https://api.cartolafc.globo.com/)
    - [Alerações de 2016 na API](https://github.com/wgenial/cartrolandofc/blob/master/nova-api.md)
- Usar framework JS [Vue.JS](https://vuejs.org/) ou
[SharePoint framework](https://github.com/SharePoint/sp-dev-docs)

## Especificações funcionais

### Tela Inicial

#### Template

Desenvolver o HTML responsivo utilizando a 
estrutura do Bootstrap com base no Wireframe;

#### Ranking

Criar uma página para montar uma tabela de classificação de times de 
https://api.cartolafc.globo.com/clubes 
exibindo: posicao | Escudo (45x45) | abreviacao (e um tooltip com o "nome")

* Ordenado por posição.

#### Busca de times

A tela deverá ter um input de busca para pesquisar os 
times em: https://api.cartolafc.globo.com/times?q=

O resultado deverá ser exibido:

nome
nome_cartola

* deverá conter paginação de 5 em 5;

## Plus

- Utilizar o proprio ambiente do SharePoint
[Dev Program](https://profile.microsoft.com/RegSysProfileCenter/wizardnp.aspx?wizid=14b845d0-938c-45af-b061-f798fbb4d170&lcid=1033)

    ***O dev program é um meio de utilizar o SharePoint gratuitamente***

    ***Caso utilize o ambiente sharepoint crie um estrutura de lista 
    personalizada com o nome "Times" com as mesmas propriedades 
    da API utilizada***

    ***Utilizar o
    [PnP-JS-Core](https://github.com/SharePoint/PnP-JS-Core) para 
    comunicação com as apis do sharepoint ou alguma lib para http 
    request's***

- Testes automatizados

- Utilizar algum pré-processador CSS.

## O que será avaliado?
- Organização do projeto
- Lógica do código
- Uso do Git