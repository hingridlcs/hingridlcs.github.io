---
layout: default
title: "Iniciando HTML"
---

O que é o HTML?

HTML - Hyper-Text Markup Language (Linguagem de Marcação de Conteúdo)

Responsavel para informar ao navegador como o conteudo vai estar estrutrada na pagina Web.
Se não houvesse o HTML a pagina seria um texto sem graça, então o HTML faz a formatação, inclui imagens, direciona a outros links e se existe tabela como será montada, se a pagina possui metadados que faz isso tambem.
O HTML possui regras com semantica que são as tags e serão mostrados em blocos com estruturas.

<img src="imagens/sematica_tag" alt="Semantica de Tags">

Um arquivo HTML deve possui essa 1a linha de comando que é a declaração de um tipo de documento.
```
<!DOCTYPE html>
```
A 2a linha de comando que mostra o Inicio e Fim do HTML.

```
<html></html>
```
A 3a linha é de inicio e Fim do cabeçalho da página.

```
<head></head>
```

Nessa 3a linha nem tudo será mostrado a página mas terá informações importantes para o controle de sites de buscas que são as metas tags, scripts e titulo da página.

```
<head>
        <title>Título da Página</title>
        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <meta name="description" content="descrição da página">
        <meta name="keywords" content="Palavras Chaves, Separadas, Por,Virgulas, Minha Pagina, Pagina 01">
</head>
```

Na 4a linha onde estará o conteudo da página podendo ter texto, imagens, vídeos, jogos, audio ou qualquer outra coisa.
```
<body></body>

```

Abaixo a estrutura de uma página HTML

<img src="imagens/estrutura_HTML" alt="Estrutura HTML">

Segue abaixo algumas tags mais utilizadas

Serve para escrever textos e o browser insere uma linha antes e depois da tag.

        <p>Escrevendo um parágrafo</p>


Insere uma imagem inserir um texto e até dimensionar a imagem.

        <img src="img_girl.jpg" alt="Menina de saia" width="500" height="600>


Define cabeçalho que vai da numeração de 1 a 6 e as fontes são exibidas do tamanho maior para o menor <h1> - <h6>.

        <h1>Cabeçalho 1</h1>
        <h2>Cabeçalho 2</h2>
        <h3>Cabeçalho 3</h3>


Define uma lista com marcadores.

        <ul>
        <li>Papel</li>
        <li>Canetas</li>
        <li>Lápis</li>
        </ul>


Utilizado para navegar de uma página para outra.

        <a href="https://www.w3schools.com">Visite W3Schools.com!</a>

Na página da <a href="https://www.w3schools.com/tags/tag_ul.asp">W3schools</a> você consegue estudar e conhecer outras tags.