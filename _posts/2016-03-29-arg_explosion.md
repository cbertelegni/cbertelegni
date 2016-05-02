---
layout: post
title:  "Cómo el voto en la argentina formó una nueva “división” política"
date:   2016-04-06 -0300
categories: dataviz
description: (Map, d3js). Mapa que muestra la distancia entre los distritos desdepues de las elecciones 2015 en Argentina
---

<iframe id="_app" frameborder="0" width="100%" height="900" scrolling="no" src="http://especiales.lanacion.com.ar/multimedia/proyectos/15/elecciones/eleccione_2015_arg_ballo_explosion/"></iframe>

## Cómo se calcula la distancia

La distancia entre dos distritos es establecida en base a la diferencia de porcentaje de los mismos y transformado en un valor equivalente en pixeles.

A esta comparación se le agrega una variable más, si en los dos distritos a comparar el ganador es el mismo o no. En el caso que el ganador sea el mismo será la diferencia del primero con el segundo transformado a un número absoluto. En el caso que sean diferentes los ganadores, El primer valor es transformado a un número negativo y luego se procede de la misma manera, se obtiene la diferencia del primero con el segundo, se convierte en un valor absoluto y este es convertido a un valor equivalente en pixeles.

![Cómo se calculó la distancia](http://i.imgsafe.org/03abff8.jpg)

Este mapa fue publicado el [blog de La Nación Data](http://blogs.lanacion.com.ar/data/sin-categoria/elecciones-2015-el-efecto-de-las-votaciones-en-los-distritos-de-la-argentina/){:target="_blank"}
