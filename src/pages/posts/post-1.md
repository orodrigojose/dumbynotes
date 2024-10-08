---
layout: "../layouts/PostLayout.astro"
title: "Minha primeira postagem em meu projeto :)"
pubDate: 2024-09-14
description: 'Estou tentando criar um blog utilizando o framework AstroJs :)'
author: 'orodrigojose'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "blogging", "learning in public"]
---

# Isto é um título muito legal

Como é visto anteriormente, alguns conteúdos materializados
olhe logo abaixo

## Código fonte
_um simples código_

```astro
---

const test = ""
---

<style>
    .post-container {
        display: flex;
        flex-direction: column;

        width: 80%;
    }

    .post-actions {
        width: 74%;
    }

.post-actions > .action {
        color: white;
        font-weight: bolder;
        display: flex;
        align-items: center;
        gap: 10px;
        text-decoration: none;
    }

    .post-informations {
        margin: 10px 0;
        color: var(--secondary-text-color);
    }
</style>
```
