---
layout: produto
title: Produtos para manutenção industrial
menu-title: Produtos
permalink: /produtos/
excerpt: >
  A Endutek fornece todos os itens necessários para montagem e manutenção industrial. Veja detalhes dos tipos de mangueiras, conexões, tubos, entre outros produtos de manutenção industrial.
destaques:
  - 
    img: abracadeiras.jpg
    title: Abraçadeiras
    link: _categorias/abracadeiras.md
  - 
    img: borrachas.jpg
    title: Borrachas
    link: _categorias/lencois-de-borracha.md
  -
    img: conexoes-galvanizadas.jpg
    title: Conexões Galvanizadas
    link: _produtos/conexoes/conexoes-galvanizadas.md
  -
    img: conexoes-hidraulicas.jpg
    title: Conexões Hidráulicas
    link: _produtos/conexoes/conexoes-hidraulicas.md
  -
    img: conexoes-pneumaticas.jpg
    title: Conexões Pneumáticas
    link: _produtos/conexoes/conexoes-pneumaticas.md
  -
    img: correias.jpg
    title: Correias
    link: _categorias/correias-e-polias.md
  -
    img: engates-rapidos.jpg
    title: Engates
    link: _categorias/engates-rapidos.md
  -
    img: flexiveis-metalicos.jpg
    title: Flexíveis Metálicos
    link: _categorias/flexiveis-metalicos.md
  -
    img: lubrificacao.jpg
    title: Lubrificação
    link: _categorias/lubrificantes-industriais.md
  -
    img: rodizios.jpg
    title: Rodízios
    link: _categorias/rodizios-e-rodas.md
  -
    img: valvula-de-esfera.jpg
    title: Válvulas
    link: _categorias/valvula-de-esfera.md
sass: >

---



A Endutek fornece todos os itens necessários para montagem e manutenção industrial. Veja detalhes dos tipos de mangueiras, conexões, tubos, entre outros produtos de manutenção industrial.

## Destaques

<div data-grid="wrap">
  {% for p in page.destaques %}
    <div data-grid="column justify" class="produto-relacionado">
      <div class="produto-thumb" data-grid="center">
        <img src="{{ img_src = site.baseurl | append: '/img/destaques/' | append: p.img }}" alt="{{ p.title }}">
      </div>
      <div data-cell="shrink">
        <a href="{{ link p.link }}">{{ p.title }}</a>
      </div>
    </div>
  {% endfor %}
</div>

<p class="only-mobile" data-grid="end"><a href="#lista-produtos" data-btn="round brand" onclick="scrollToTarget('.lista-produtos');">Conheça toda a linha...</a></p>

