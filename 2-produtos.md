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
    link: /produtos/abracadeiras/
  - 
    img: borrachas.jpg
    title: Borrachas
    link: /produtos/lencois-de-borracha/
  -
    img: conexoes-galvanizadas.jpg
    title: Conexões Galvanizadas
    link: /produtos/conexoes/conexoes-galvanizadas/
  -
    img: conexoes-hidraulicas.jpg
    title: Conexões Hidráulicas Ermeto
    link: /produtos/conexoes/conexoes-hidraulicas/
  -
    img: conexoes-pneumaticas.jpg
    title: Conexões Pneumáticas Festo
    link: /produtos/conexoes/conexoes-pneumaticas/
  -
    img: correias.jpg
    title: Correias
    link: /produtos/correias-e-polias/
  -
    img: engates-rapidos.jpg
    title: Engates
    link: /produtos/engates-rapidos/
  -
    img: flexiveis-metalicos.jpg
    title: Flexíveis Metálicos
    link: /produtos/flexiveis-metalicos/
  -
    img: lubrificacao.jpg
    title: Lubrificação
    link: /produtos/lubrificantes-industriais/
  -
    img: rodizios.jpg
    title: Rodízios
    link: /produtos/rodizios-e-rodas/
  -
    img: valvula-de-esfera.jpg
    title: Válvulas
    link: /produtos/valvula-de-esfera/
---

A Endutek fornece todos os itens necessários para montagem e manutenção industrial. Veja detalhes dos tipos de mangueiras, conexões, tubos, entre outros produtos de manutenção industrial.

<div class="destaque-mangueiras">
  <h2>Mangueiras</h2>
  <div data-grid>
    <div class="produto-relacionado">
      <a href="/produtos/mangueiras-hidraulicas/">
        <img src="/img/destaques/mangueiras-hidraulicas.jpg" alt="Mangueiras Hidráulicas">
        <div>Mangueiras Hidráulicas</div>
      </a>
    </div>
    <div class="produto-relacionado">
      <a href="/produtos/mangueiras-espiraladas/">
        <img src="/img/destaques/mangueiras-espiraladas.jpg" alt="Mangueiras Espiraladas Kanaflex">
        <div>Mangueiras Espiraladas Kanaflex</div>
      </a>
    </div>
    <div class="produto-relacionado">
      <a href="/produtos/mangueiras-industriais/">
        <img src="/img/destaques/mangueiras-industriais.jpg" alt="Mangueiras Industriais">
        <div>Mangueiras Industriais</div>
      </a>
    </div>
  </div>
</div>

## Destaques

<div data-grid="wrap">
  {% for p in page.destaques %}
    <div class="produto-relacionado" data-grid="center">
      <a href="{{ site.baseurl }}{{ p.link }}" class="produto-thumb">
        <img src="{{ img_src = site.baseurl | append: '/img/destaques/' | append: p.img }}" alt="{{ p.title }}">
        <div>{{ p.title }}</div>
      </a>
    </div>
  {% endfor %}
</div>

<p class="only-mobile" data-grid="end"><a href="#lista-produtos" data-btn="round brand" onclick="scrollToTarget('.lista-produtos');">Conheça toda a linha...</a></p>

