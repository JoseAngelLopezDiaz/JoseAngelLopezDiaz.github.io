---
title: José Ángel López Díaz
description: Entusiasta ingeniero de la energía y los recursos minerales
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Bienvenido a mi web! Cualesquiera que hayan sido los motivos que te trajeron aquí, ahora no importan. Estás aquí, y estás leyendo esto. Disfruta. "
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
    Learn more
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Get the code
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

Goldydocs provides a single web UI providing visibility into porridge
temperature, chair size, and bed softness metrics! You can even find out who's
been eating **your** porridge.

(Sadly, Goldydocs isn't a real project, but you can use this site as an example
to create your own real websites with [Docsy](https://docsy.dev))

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="" icon="fa-book" %}}

Mi pasión, aparte de la ingeniería de minas, es la literatura.

Quizás sea lo que mejor se me da, o quizás crea que es lo que mejor se me da.

{{% /blocks/feature %}}

{{% blocks/feature
  title="Me encanta el ajedrez" icon="fab fa-chess"
  url="https://github.com/google/docsy-example"
%}}

Puedes jugar [conmigo](https://www.chess.com/member/presio213)
en chess.com, si te apetece perder.

{{% /blocks/feature %}}

{{% blocks/feature
  title="Pulsa aquí para una mejor expreiencia" icon="fab fa-x-languaje"
  url="https://x.com/docsydocs"
%}}

Me encantan los idiomas, también.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

This is the second section

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

This is the another section with center alignment

{{% /blocks/section %}}
