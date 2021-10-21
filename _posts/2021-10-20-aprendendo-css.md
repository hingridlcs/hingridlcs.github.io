---
layout: default
title: "Aprendendo CSS"
---
CSS é a abreviação de Cascading Style Sheets.

Com o surgimento da Web, as paginas antigamente não eram muito amigáveis sendo muito trabalhoso criar projetos interessantes, pois HTML não era muito produtivo para realizar estilos além de serem todas as paginas elaboradas em forma de tabelas.

O CSS veio para revolucionar as aparencias das páginas Web e a W3C ajudou a dar um estilo e formatação as páginas, criando uma versão interessante de página utlizando a padronização <a href="https://en.wikipedia.org/wiki/Document_Object_Model" target="_blank">DOM </a>(modelo lógico em nós organizados em forma de árvore).

Essa padronização ajuda na compatibilidade dos navegadores, recursos na aparencia nas páginas Web e a manutenção se torna simples poupando tempo e dando maior flexibilidade para manter os projetos atualizados. Vamos entender com exemplos as 4 formas principais desses seletores:

- Classes;

        Exemplo: .container{}

- Identificadores;

        Exemplo: #menu {}

- Tags;

        Exemplo: a{}

- Atributos.

        Exemplo: a[target="_blank"] {}


Na versão <a href="https://www.w3c.br/divulgacao/guiasreferencia/css2/#mod-fontes">CSS 2.1</a> foram criados muitas tecnicas de designers utilizando Float, Position e Clear mas eram complicadas de manter e veio uma especificação nova chamada CSS Grid Layout onde os elementos filhos do container que divide a grade pode ser posicionados livremente podendo dessa forma criar layouts muito melhores.

Sobre o Grid Layout (Box Model level 3)
nessa versão css foi criada propriedade box-sizing (calcula a largura e altura de um elemento e como se ajusta aos outros elementos)
Exemplo:
box-sizing: border-box;
O padding e o border não irão mais alterar as dimensões de um elemento

Dessa forma Grid Layout se tornou responsivo, melhor controle no alinhamento no grid e nos seus elementos e podendo até mesmo adicionar grids adicionais fora do principal e criação do x-index para controlar conteudos sobrepostos.

O CSS 3 mudou tudo as especificações foram mudadas em modulos e cada um tem a sua aprovação independente. Essa versão vieram as animações ( controle de rotação, movimento e transição ), criações de variáveis, funções e soluções como CSS <a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/" alt="_blank">Flexible Box Layout Model (Flexbox)</a>.

Variáveis e funções no CSS

    Declaração

        :root {
            --my-cor-bg-principal: brown;
        }

    Utilizando variável na função var()

        p {
        background-color: var(--my-cor-bg-principal);
        }

Alguns links para estudos

    https://desenvolvimentoparaweb.com/css/variaveis-css-guia-pratico/
    https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties
    https://www.ranoya.com/books/public/css/funcoescss.php


Existem alguns Pré-processadores CSS como Sass, Less e Stylus entre outros. Eles são interpretadores de código e cada um com suas regras geram um codigo CSS. Nos pré processadores podemos criar variáveis, condicionais, laços, repetições, importações e até heranças.

Há os Frameworks que facilitam muito o desenvolvimento dos projetos Web. Segue alguns dos mais utilizados frameworks como Bootstraps, Materialize CSS, Foundation e o Semantic UI.
