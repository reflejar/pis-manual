![Header](ryder_isologotipos.png)

***

## PIS (Pesticidas Introducidos Silenciosamente)

## Índice

* [1. Nombre del proyecto](#1-nombre-del-proyecto)
* [2. Descripción y contexto](#2-descripción-y-contexto)
* [3. Fundamento del software](#3-fundamento-del-software)
* [4. Guía de instalación](#4-guía-de-instalación)
* [5. Autor](#5-autor)
* [6. Versión](#6-versión)
* [7. Licencia](#7-licencia)

***

## 1. Nombre del proyecto

- PIS (Pesticidas Introducidos Silenciosamente)

## 2. Descripción y contexto

**PIS “Pesticidas Introducidos Silenciosamente”** es una iniciativa creada por Democracia en Red. Es una plataforma web que engloba varias herramientas para reducir el impacto de los agrotóxicos en nuestros cuerpos; en términos generales:

1. Landing Page que brinda información y presenta todas las herramientas.

2. Mapa interactivo de zonificación normativa de la provincia de Buenos Aires, donde se pueden observar las zonas donde está prohibido fumigar con glifosato, según la normativa de cada departamento.

3. Mapa de normativa comparada entre distritos rankeado a través de una metodología específica que toma en cuenta las zonas de exclusión, amortiguamiento y otras variables a fines.

4. Plataforma de análisis de los censos agropecuarios donde se visualizan los principales indicadores de relevancia desde las bases de datos servidos por INDEC.

5. Mapa interactivo de Testeos de la provincia de Buenos Aires donde se observan los resultados de análisis en orina, agua, materia vegetal, etc, con el objetivo de determinar si se observan agrotóxicos.

6. Buscador de jurisprudencia al respecto del uso de glifosato.



## 3. Fundamento del software

El proyecto está desarrollado en 3 tecnologías diferentes.

- [Python Dash](https://dash.plotly.com/) para el mapa de de normativas, la plataforma ambiental y el buscador de jurisprudencia
- [R Shiny](https://shiny.posit.co/) para el mapa de testeos
- Stack web básico para landing y web descriptiva

Se desarrolló con enfoque de arquitectura distribuida en donde cada uno de estos tres componentes funcionan asiladamente por varios motivos:

- El expertiz de lxs diferentes desarrolladorxs de [reflej.ar](https://reflej.ar/). Algunxs habituan a python y otrxs a R
- Para distribuir la carga de procesamiento en diferentes centros de cómputos
- Algunos procesamientos son más eficientes en Python y otros en R


## 4. Guía de instalación

Hay dos formas de instalar PIS: Una es de forma clásica, vernáculas, descargando, haciendo setup y corriendo cada uno de los 3 repositorios en una terminal por repositorio. El manual lo pueden encontrar haciendo [click aqui](instalaciones-vernaculas.md)

La segunda forma es utilizando Docker y `docker compose`. En solo un paso se instala y conectan todos. El manual lo pueden encontrar haciendo [click aqui](instalacion-docker.md)

* [pis-web on Github/DemocraciaEnRed](https://github.com/DemocraciaEnRed/pis)
* [pis-dash on Github/DemocraciaEnRed](https://github.com/DemocraciaEnRed/pis-dash) 
* [pis-shiny on Github/DemocraciaEnRed](https://github.com/DemocraciaEnRed/pis-shiny)


> Los repositorios originales y de desarrollo se encuentran en 
> * [pis-web on Github/reflejar](https://github.com/reflejar/pis)
> * [pis-dash on Github/reflejar](https://github.com/reflejar/pis-dash) 
> * [pis-shiny on Github/reflejar](https://github.com/reflejar/pis-shiny)

## 5. Co-autoría

Fundación [Democracia en Red](https://democraciaenred.org) junto con [reflej.ar](https://reflej.ar/).

## 6. Versión

La información referente a la versión del portál de PIS puedes encontrarla [aquí](https://github.com/DemocraciaEnRed/pis/releases)

## 7. Licencia

La licencia es GNU, puedes encontrarla en el siguiente enlace [LICENSE.MD](https://github.com/DemocraciaEnRed/pis/blob/main/LICENSE)



