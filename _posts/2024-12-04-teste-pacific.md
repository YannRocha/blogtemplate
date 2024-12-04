---
layout: exemplo
cover: "assets/images/cover3.jpg"
navigation: true
title: "Pacific"
date: 2024-12-04 10:18:00
tags: exemplo video imagem texto
subclass: "post"
logo: "assets/images/ghost.png"
author: "Yann Soares"
categories: exemplo
---

# Bem-vindo ao Meu Blog!

<p>Este é um exemplo de postagem para demonstrar como incluir texto, imagens e vídeos no seu blog do Jekyll.</p>

## Imagem de Destaque

![Imagem de exemplo]({{ "/assets/images/cover2.jpg" | relative_url }})

> **Nota:** test da nota.

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum.</p>

## Vídeo do AWS S3

<video controls width="560" height="315" preload="auto">
  <source src="https://pacificsecvideos.s3.sa-east-1.amazonaws.com/teaser_v5.mp4" type="video/mp4">
  Seu navegador não suporta a reprodução de vídeo.
</video>

## Vídeo do youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/F8iOU1ci19Q?si=MGASyO_IKjZvLnUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
