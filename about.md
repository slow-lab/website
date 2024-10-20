---
layout: default
title: "SlowLab Team"
label: "El equipo"
---

<div class="two-columns normal">
  <div class="col-text small green-bg">
      <h1 class="yellow">
        En la intersección entre el slow movement y low tech.
      </h1>
    </div>
 
  <div class="col-text bigger green-bg">
    <p class="yellow">
        Somos un colectivo de diseñadores, makers y arquitectos que busca crear conciencia y promover modos de vida resilientes.
        <br><br>Organizamos eventos sociales y creamos artefactos para abrir conversaciones alrededor de cómo integrar técnicas ancestrales a nuestro contexto actual.
        <br><br>Cuestionamos y rediseñamos las herramientas que utilizamos en nuestra vida cotidiana para depender menos de la alta tecnología.
        <br><br>Hoy nos encontramos en Barcelona y en México.
    </p>
  </div>
</div>

<!-- Section banner -->
{% include banner.html %}

<!-- Team -->
<div class="cards team">
{% assign founders = site.members | where: "position", "Cofundadora" %}
{% for member in founders %}
<div class="card-team">
    <img class="avatar" src='{{ member.photo | relative_url}}'>
    <div class="content">
        <h1>{{ member.name }}</h1>
        <h3>{{ member.position }}, {{ member.location }}</h3>
        <p>{{ member.content | markdownify }}</p>
    </div>
</div>
{% endfor %}
</div>

<!-- Cities -->
<div class="central lily-bg">
    <h1 class="title">¿Dónde estamos ubicadas?</h1>
    <div class="row">
        <div>
            <img src="{{'/assets/images/team/akasha-hub.jpg' | relative_url }}" class="round">
            <h1>Barcelona</h1>
            <h3>Akasha Hub</h3>
        </div>
        <div>
            <img src="{{'/assets/images/team/comite.jfif' | relative_url }}" class="round">
            <h1>México</h1>
            <h3>Comité</h3>
        </div>
    </div>
</div>

<!-- Collab -->
<div class="central white-bg green">
<h1>La colaboración es la llave de todo lo que hacemos</h1>
<p>Siempre nos gusta colaborar y escuchar nuevas ideas.
Déjanos un mensaje y te responderemos slowly!</p>
<div class="row">
{% assign friends = site.members | where: "position", "Friend" %}
{% for member in friends %}
<div class="friend"> 
<img src="{{ member.photo | relative_url}}" class="square">
<h3>{{ member.name }}</h3>
<p>{{member.content}}</p>
</div>
{% endfor %}
</div>

</div>