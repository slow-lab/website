---
layout: default
title: "SlowLab Projects"
label: "Nuestras iniciativas"
---

<div class="two-columns">
  <div class="col-text green-bg">
      <h1 class="yellow">
        Proyectos
      </h1>
    <p class="yellow">
    Conoce nuestros ultimos proyectos en donde usamos alternativas low tech de manera entretenida.
    <br><br>Buscando generar consciencia y detonar conversaciones que nos ayuden a imaginar un futuro mas amigable con el medio ambiente.
    </p>
    </div>

  <div class="col-img projects outline">
  </div>
</div>

<!-- Section banner -->
{% include banner.html %}

<!-- Projects cards -->
<div class="cards projects">
{% for post in site.posts %}
  {% include projects.html %}
{% endfor %}
</div>