---
layout: post
title:  '[pt-BR] Use Background Jobs e não deixe o usuário esperando'
date:   2013-10-31 12:15:36
categories: rails
helabs: true
link: 'http://helabs.com.br/blog/2013/10/31/use-background-jobs-e-nao-deixe-o-usuario-esperando/'
---

Muitas aplicações Rails precisam enviar emails e muitas deixam o usuário esperando até que o mesmo seja enviado e não usam background jobs para fazer esse trabalho. Vamos tentar melhorar isso.