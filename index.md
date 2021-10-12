---
layout: default
title: Blog da Hingrid
---
Eu criei esse blog de estudos para quem quer iniciar ou tem curisidade de saber de algumas tecnologias.

Eu sentia a necessidade de estudar e sabia das minhas dificuldades, mas eram tantas ferramentas novas e melhores práticas que até mesmo com a minha experiência não sabia por onde começar.

Minha experiência é maior em back-end, então decidi iniciar por onde sempre vou deixando de me apronfundar, que são as tecnologias de front-end.

Portanto no inicio vou dar mais enfase nas tecnologias Front-End assim quem não tem experiência pode iniciar os estudos por HTML, CSS e Javascript.

Eu utilizo as ferrramentas VSCode da Microsoft, Node.js e Git para aprender.

# Meus artigos

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
