---
layout: post
title:  '[pt-BR] Manipulando imagens on-the-fly pela URL'
date:   2013-08-28 12:15:36
categories: rails
helabs: true
link: 'http://helabs.com.br/blog/2013/08/28/manipulando-imagens-on-the-fly-pela-url/'
---

Digamos que você possui uma API e precisa que algumas imagens sejam cropadas, ou redimencionadas, de vários tamanhos on-the-fly pela URL. Por exemplo: /image/1/w/300/h/400 Retornaria uma imagem que você já salvou redimencionada para 300x400. É possível fazer mais do que redimencionar a imagem, mas vamos nos focar somente nisso por enquanto.