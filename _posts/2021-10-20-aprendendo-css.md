---
title: "Aprendendo CSS"
---
CSS é a abreviação de Cascading Style Sheets.

Com o surgimento da Web, as páginas antigamente não eram muito amigáveis sendo muito trabalhoso criar projetos interessantes. O HTML não era muito produtivo para realizar estilos, além de serem todas as paginas elaboradas em forma de tabelas.

O CSS veio para revolucionar as aparencias das páginas Web e a W3C ajudou a dar um estilo e formatação as páginas, criando uma versão interessante utlizando a padronização [DOM](https://en.wikipedia.org/wiki/Document_Object_Model){:target="_blank"} (modelo lógico em nós organizados em forma de árvore).

Essa padronização ajuda na compatibilidade dos navegadores, recursos na aparência e a manutenção se torna simples, poupando tempo e dando maior flexibilidade para manter os projetos atualizados. 

Vamos entender com exemplos as 4 formas principais desses seletores:

- Classes;
  <br/>
  Exemplo: `.container{}`

- Identificadores;

        Exemplo: #menu {}

- Tags;

        Exemplo: a{}

- Atributos.

        Exemplo: a[target="_blank"] {}


Na versão [CSS 2.1](https://www.w3c.br/divulgacao/guiasreferencia/css2/#mod-fontes){:target="_blank"} foram criadas muitas técnicas de designers utilizando as propriedades Float, Position e Clear mas eram complicadas de manter e apareceu uma especificação nova chamada CSS Grid Layout onde os elementos filhos do container que divide a grade pode ser posicionados livremente havendo dessa forma a criação de layouts muito melhores.


![Box Model](/imagens/box_model.png)

Nessa versão foi criada propriedade box-sizing (calcula a largura e altura de um elemento e como se ajusta aos outros elementos).

Exemplo:

`box-sizing: border-box;`

O padding e o border não irão mais alterar as dimensões de um elemento.

Dessa forma Grid Layout se tornou responsivo, melhor controle no alinhamento no grid e nos seus elementos, podendo até mesmo adicionar grids adicionais fora do principal e a criação do z-index para controlar conteudos sobrepostos.

O CSS 3 alterou tudo, as especificações foram alteradas em modulos e cada um tem a sua aprovação independente. Nessa versão vieram as animações ( controle de rotação, movimento e transição ), criações de variáveis, funções e soluções como CSS [Flexible Box Layout Model (Flexbox)](https://css-tricks.com/snippets/css/a-guide-to-flexbox/){:target="_blank"}.

Variáveis e funções no CSS

    Declaração

        :root {
            --my-cor-bg-principal: white;
        }

    Utilizando variável na função var()

        p {
        background-color: var(--my-cor-bg-principal);
        }

Alguns links para estudos

[https://desenvolvimentoparaweb.com/css/variaveis-css-guia-pratico/](https://desenvolvimentoparaweb.com/css/variaveis-css-guia-pratico/)

[https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

[https://www.ranoya.com/books/public/css/funcoescss.php](https://www.ranoya.com/books/public/css/funcoescss.php)


Existem alguns pré-processadores CSS como Sass, Less e Stylus entre outros. Eles são interpretadores de código e cada um com suas regras geram um codigo CSS. Nos pré-processadores podemos criar variáveis, condicionais, laços, repetições, importações e até heranças.

Há os Frameworks que facilitam muito o desenvolvimento dos projetos Web. Segue alguns dos mais utilizados frameworks como Bootstraps, Materialize CSS, Foundation e o Semantic UI.
