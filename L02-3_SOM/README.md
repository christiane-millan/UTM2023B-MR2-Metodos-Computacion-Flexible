[`Métodos de Computación Flexible`](../README.md) > `2. Redes Neuronales Artificiales - Red de Kohonen`

# Unidad 2. Redes Neuronales Artificiales -Red de Kohonen

**Contenido.**

- [Unidad 2. Redes Neuronales Artificiales -Red de Kohonen](#unidad-2-redes-neuronales-artificiales--red-de-kohonen)
  - [Introducción](#introducción)
    - [Mapa Auto-Organizativo](#mapa-auto-organizativo)
  - [1. Entrenamiento de un SOM](#1-entrenamiento-de-un-som)

**Objetivo.**

En esta clase el alumno conocerá:

El concepto de los Mapas Auto-Organizativos (MAO).
Los principios neurofisiológicos de las MAO.
La regla para realizar el entrenamiento de una Red Unidimensional de Kohonen.
La implementación de MAO para visualización de clústers.


## Introducción

Los  Mapas Auto-Organizativos (SOM, Self-Organizing Maps) son un tipo de algoritmo de aprendizaje no supervisado.

El agrupamiento (o análisis de grupos) es una técnica que nos permite encontrar grupos de objetos similares que esta mas relacionados entre sí que con otros de otro grupo. 
Ejemplos de aplicaciones de agrupamiento orientadas al negocio son: 

* el agrupamiento de documentos, 
* música 
* y películas de diferentes temas, 
* o encontrar clientes que tienen intereses similares basados en comportamiento de compras comunes com una base de un motor de recomendaciones.


### Mapa Auto-Organizativo

* Los Mapas Auto-Organizativos o las Redes de Kohonen (SOM, por las siglas en inglés de Self-Organization Map) es un tipo de red no supervisada, es decir, cuando no se conoce al principio los objetos que se están aprendiendo, estos son agrupados pos sus similitudes.

* Están basadas en un aprendizaje competitivo, es decir, que las neuronas compiten entre ellas para ser activadas o encendidas.

Los SOM al igual que el cerebro humano tienen la tarea de mapear información de alta dimensión (n dimensiones) en áreas de una cuadrícula de baja dimensión (g dimensiones) para dibujar un mapa del espacio de alta dimensión.

Existen dos espacio en los cuales trabaja el SOM:

* El espacio de entrada N dimensional y

* La cuadrícula de G dimensiones en la cual las neuronas SOM se encuentran e indica las relaciones del vecindad entre las neuronas y, por lo tanto, la topología de la red.

## 1. Entrenamiento de un SOM

[`Aprendizaje SOM unidimensional`](./code/som_unidimensional.ipynb)


[`Anterior`](../L02-NNets/README.md) | [`Siguiente`](../README.md)
