# Cálculo de f'c por esclerometría (NTP 339.181) 🏗️

Este repositorio contiene un algoritmo desarrollado en Python para procesar datos de ensayos no destructivos (Esclerometría) y determinar la resistencia a la compresión del concreto.

## 📋 Descripción Técnica

El código ha sido programado para seguir **al pie de la letra** los criterios de aceptación y descarte establecidos en la **Norma Técnica Peruana NTP 339.181** (equivalente a ASTM C805).

A diferencia de cálculos genéricos, este script integra las curvas de correlación específicas del modelo de esclerómetro **Dana HT-225**, garantizando precisión para este equipo en particular.

### 🚀 Características Principales

* **Cumplimiento Normativo:** Aplica estrictamente los criterios de la NTP 339.181 para el promedio y descarte de lecturas erráticas (rebotes que difieren en más de 6 unidades del promedio).
* **Curvas Calibradas:** Digitalización de las curvas de resistencia vs. índice de rebote del fabricante **Dana (Modelo HT-225)**.
* **Visualización de Datos:** Generación de gráficos para analizar la dispersión de las lecturas.
* **Automatización:** Procesa múltiples lecturas y ángulos de disparo (0°, -90°, +90°) de manera inmediata.

## 🛠️ Requisitos

Para ejecutar este script necesitas tener instalado Python 3.x y las siguientes librerías de análisis de datos:

* `numpy`
* `pandas`
* `matplotlib`

Puedes instalar las librerias con el siguiente comando:
```bash
pip install numpy pandas matplotlib
