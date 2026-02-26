---
title: José Ángel López Díaz
description: Entusiasta ingeniero de la energía y los recursos minerales. Ostensiblemente, tengo demasiado tiempo libre.
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Saludos, anónimo desconocido. Soy José Ángel López Díaz. "
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!--
  Want a cover without an image?
  Add the following argument to the blocks/cover shortcode:
    color="primary bg-gradient td-below-navbar"
-->

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

<!-- prettier-ignore -->
<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Sobre mí
    {{% _param FA brands flask "" %}}
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Contacto
    {{% _param FA brands user "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

Cualesquiera que hayan sido los motivos que te trajeron aquí, ahora no importan. Estás aquí, y estás leyendo esto. Disfruta.



{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="Mi pasión, aparte de la ingeniería de minas, es la literatura.
" icon="fa-book" %}}

Quizás sea lo que mejor se me da, o quizás sea lo que creo que es lo que mejor se me da. En cualquier caso, he aquí mi [obra](MI LIBRO)

{{% /blocks/feature %}}

{{% blocks/feature
  title="Me encanta el ajedrez" icon="fab fa-chess"
  url="https://github.com/google/docsy-example"
%}}

Puedes jugar [conmigo](https://www.chess.com/member/presio213)
en chess.com, si te apetece perder. Mi foto de perfil es una taza con la cara de Nicolas Cage. No tiene pérdida.

{{% /blocks/feature %}}

{{% blocks/feature
  title="Pulsa [aquí](WEB A PONER) para una mejor expreiencia" icon="fab fa-music"
  url="https://x.com/docsydocs"
%}}

Adoro la música, también, lo cual me hace humano, en contra de lo que pueda parecer. "Sin música, la vida sería un error", que decía Nietzsche, con quien identifico porque yo también soy nihilista los lunes por la mañana.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

This is the second section

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

This is the another section with center alignment

{{% /blocks/section %}}
