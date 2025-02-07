---
title: Hello World
layout: "base.njk"
---

<link rel="stylesheet" href="/src/styles.css">

<div class="center-content">

# Acerca de mí

¡Hola! Mi nombre es __*[Tu Nombre]*__. Soy [tu profesión o pasatiempo principal]. Aquí hay un poco más sobre mí:

## Educación

[Tu título o certificación]
[Otra educación relevante]

## Experiencia

[Tu trabajo actual o más reciente]
[Otro trabajo relevante]

## Habilidades

[Habilidad 1]
[Habilidad 2]
[Habilidad 3]

## Pasatiempos

[Pasatiempo 1]
[Pasatiempo 2]
[Pasatiempo 3]

## Contacto

Puedes contactarme en [tu correo electrónico] o seguirme en [tu red social favorita].

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})
{% endfor %}
</div>