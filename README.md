# Network Medicine: teoría de grafos aplicada con `python`

Los contenidos presentados en este repositorio conforman la segunda parte de la asignatura **Network Medicine** del [Máster en Bioinformática, Biología Computacional y Medicina Personalizada](https://biocom.webs.upv.es/) de la [Universitat Politècnica de València](http://www.upv.es/es).

Esta asignatura está impartida por:

- Lucas Goiriz Beltrán,  M.Sc. &emsp; *Instituto de Biología Integrativa y de Sistemas (I2SysBio, UV - CSIC) & Departamento de Matemática Aplicada (UPV)*
- Alberto Conejero Casares, Full. Prof. &emsp; *Departamento de Matemática Aplicada (UPV)*

------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Introducción

Bienvenidos a la segunda parte de la asignatura de **Network Medicine**. En esta parte introduciremos el módulo `networkx` de `python`, el cual nos permitirá crear y analizar grafos. Por el camino, repasaremos varios de los conceptos (nomenclatura, métricas y algoritmos) introducidos en la primera parte de la asignatura.

Finalmente, veremos varios ejemplos de redes a partir de datos reales (comenzando por ejemplos sencillos hasta presentar ejemplos más complicados).

Adicionalmente, veremos dos maneras distintas de visualizar los grafos generados (una más *user friendly* y otra más completa).

La distribución de los contenidos es la siguiente:

- Introducción a `networkx` y repaso de teoría: ficheros `1` y `1.5`
- Ejemplos de redes mediante datos reales: `2`, `3`, `4` y `5`

*Nótese que en los ficheros `2`, `3` y `4` se impulsa el uso de la librería `netwulf` para la visualización de los grafos, mientras que en el fichero `5` se emplea la librería `plotly`.

## Requisitos

Los requisitos para poder ejecutar satisfactoriamente todo el código presente en los ficheros es trabajar ya sea de forma local mediante `pip` o mediante `conda`.
Los usuarios de `conda` deberán instalar `netwulf` mediante `pip`, ya que este no se encuentra de forma nativa en los repositorios de `conda`.

## Expectativas

Para la elaboración satisfactoria del trabajo de la asignatura, es más que suficiente comprender y haber completado el fichero `1`, además de comprender los ficheros `2` y `3` (ya que estos pueden proporcionar código útil para la elaboración del trabajo). Los ficheros `4` y `5` son recursos beneficiosos a tener en cuenta, pero debido a las limitaciones de tiempo de la asignatura, sus contenidos no serán exigidos en el trabajo.
