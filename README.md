# Simulación de Dinámica de Pastos Marinos mediante Autómatas Celulares

Trabajo Práctico Final - Modelos Sistemas Biológicos.

## Descripción del Proyecto

Este repositorio contiene un modelo computacional que simula el impacto del cambio climático y la introducción de especies invasoras en las comunidades de pastos marinos del Mediterráneo. El proyecto replica los conceptos principales del artículo *"Climate change and the presence of invasive species will threaten the persistence of the Mediterranean seagrass community"* y añade nuevas dinámicas ambientales.

## Especies Modeladas

* **Nativas:** *Posidonia oceanica* (crecimiento lento, baja mortalidad) y *Cymodocea nodosa*.
* **Invasora:** *Halophila stipulacea* (alta tasa de crecimiento y fuerte competitividad).

## Escenarios y Metodología

* **Autómata Celular:** Grilla interactiva donde las celdas actualizan su estado (ocupado por una especie, vacío o "dead matte") año a año.
* **Escenarios Climáticos:** Se evalúan los escenarios de emisiones RCP 2.6 y RCP 8.5, los cuales modifican las tasas fisiológicas de las plantas.
* **Incorporación Original:** Se introdujo un sistema de eventos destructivos que ocurren cada 10 años, eliminando el 10% de la biomasa de la grilla para simular perturbaciones mecánicas o tormentas extremas.

## Ejecución del Modelo

El script principal genera animaciones en tiempo real (mapas de calor) mostrando el desplazamiento espacial de las especies a lo largo de 80 años, acompañadas de gráficos de barras dinámicos y series temporales de cobertura porcentual.
