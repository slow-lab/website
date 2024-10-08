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
<div class="carousel-projects lily-bg">
    <div class="left">
        <h1>Eventos que amamos recordar</h1>
        <span>
           <span class="proj-text" style="display:block"><h3>{{ site.posts.first.title }}</h3><p>{{site.posts.first.content}}</p></span>
           <span class="proj-text" style="display:none"><h3>{{ site.posts.last.title }}</h3><p>{{site.posts.last.content}}</p></span>
            <span class="proj-text" style="display:none"><h3>{{ site.posts.first.title }}</h3><p>{{site.posts.first.content}}</p></span>
        </span>
    </div>
    <div class="right-img">
      <img class="mySlides" src="{{ site.posts.first.image | relative_url }}" alt="test" style="display:block">
      <img class="mySlides" src="{{ site.posts.last.image | relative_url }}" alt="test" style="display:none">
      <img class="mySlides" src="{{ site.posts.first.image | relative_url }}" alt="test" style="display:none">
      <div class="nav-slides">
        <img src="{{'/assets/images/icons/arrowleft.png' | relative_url }}" alt="&#8592;" class="" onclick="plusDivs(-1)">
        <span class="nav-numbers">
        <span class="nb-slide selected" onclick="currentDiv(1)">1</span>
        <span class="nb-slide" onclick="currentDiv(2)">2</span>
        <span class="nb-slide" onclick="currentDiv(3)">3</span>
        </span>
        <img src="{{'/assets/images/icons/arrowright.png' | relative_url }}" alt="&#8592;" class="" onclick="plusDivs(+1)">        
      </div>
    </div>
</div>




<!-- Title banner -->

<div class="title-banner">
    <span><h1>Proyectos</h1></span>
    <div class="button green">descubrir más</div>
</div>
