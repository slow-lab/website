---
layout: default
title: "Slow lab"
---

<div class="two-columns">
  <div class="left green-bg">
    <span>
      <h1 class="yellow">
        Cuestionamos y rediseñamos las herramientas que utilizamos en nuestra vida cotidiana para depender menos de la alta tecnología.
      </h1>
    </span>
    <div class="button yellow">descubrir más</div>
  </div>
 
  <div class="right-img">
 </div>
</div>

<!-- Section banner -->

<div class="section-banner lily-bg">
    <span class="banner-item"><h1>Acerca de</h1></span>
    <span class="banner-item"><h1>Acerca de</h1></span>
    <span class="banner-item"><h1>Acerca de</h1></span>
    <span class="banner-item"><h1>Acerca de</h1></span>
    <span class="banner-item"><h1>Acerca de</h1></span>
</div>

<!-- Slogan -->

<div class="section-bg" id="slogan">
    <div class="slogan-frame">
        <img src="{{ '/assets/images/icons/Slowlab_Iconos_Ave_3_small.png' | relative_url }}" alt="Slow lab">
        <h1>En la intersección entre el slow movement y low tech, somos un colectivo de diseñadores, makers y arquitectos que busca crear conciencia y promover modos de vida resilientes.</h1>
        <div class="button green">descubrir más</div>
    </div>
</div>


<!-- Eventos que amamos recordar -->
<div class="events-banner lily-bg">
   <div class="left">
    <h1>Eventos que amamos recordar</h1>
        {% for post in site.posts %}
        <h3> {{ post.title }} </h3>
        <p>{{post.content}}</p>
        {% endfor %}
    </div>

</div>


<!-- Title banner -->

<div class="title-banner">
    <span><h1>Proyectos</h1></span>
    <div class="button green">descubrir más</div>
</div>
