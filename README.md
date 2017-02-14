# Teste SimbioX: Front-End Developer
Desenvolver uma aplicação para testar os 
conhecimentos Front-End com HTML, CSS e JavaScript, 
além de lógica de programação, organização e semântica.

## Sobre a Vaga
Será responsável por construir estruturas front-end 
(HTML, CSS e principalmente JavaScript) com códigos 
eficientes e reutilizáveis que se integram com outros 
sistemas e tecnologias. Participará de diferentes projetos 
(Portais Corporativos, Intranets e Sistemas on-line diversos para grandes empresas) 
desenvolvidos sob a Plataforma Microsoft SharePoint, onde é realizado um treinamento 
inicial na primeira semana para introdução e ambientação à plataforma.

Remuneração à negociar de acordo com resultado de teste prático;

## Sobre a SimbioX
A SimbioX (http://www.simbiox.com.br) é uma consultoria em TI, 
que trabalha com a plataforma Microsoft SharePoint (sugiro dar uma pesquisada nisso). 
Procuramos alguém que tenha muita disposição para aprender, pois a plataforma 
(que é um tipo de CMS avançado e muito robusto para criação de Portais Web, 
Intranets, Extranets e etc) é exclusiva e usada por grandes empresas no mercado corporativo. 
Estamos localizados na Rua Cláudio Soares, 72 – muito perto do metro Faria Lima.

## Instruções
- Faça um fork desse projeto para a sua conta pessoal do GitHub.
- Crie um README com as instruções para compilar, testar e rodar o projeto.
- O link do repositório deverá ser enviado para o e-mail
jonas.buriti@simbiox.com.br com o título **[SX] Teste Front-End Developer**

## Especificações tecnicas
- Utilizar uma lib como Bootstrap, Materialize ou alguma outra de sua preferência
- Utilizar a API [CartolaFC API] (https://api.cartolafc.globo.com/)
    - https://github.com/wgenial/cartrolandofc/blob/master/nova-api.md
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