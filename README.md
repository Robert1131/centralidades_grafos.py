# Proyecto de Grafos en Python

Este proyecto corresponde a la resolución de un problema práctico propuesto en la materia, aplicando **estructuras de datos, métricas de centralidad y visualización de grafos y árboles**.

## Temas abordados

* Cálculo de métricas de centralidad (grado, cercanía, intermediación).
* Gráfica de grafos (a partir de datos simulados en un bloque de notas).
* Gráfica de árboles (ejemplos con `networkx`).
* Reportería de los elementos que conforman la estructura (nodos, aristas, grados).
* Análisis de ventajas y desventajas de la estructura utilizada.
* Uso de un **agente de IA (ChatGPT)** en la generación del código.

---

## Requisitos

* Python 3.8 o superior
* Librerías necesarias:

```bash
pip install networkx matplotlib
```

---

## Ejecución

Para correr el programa:

```bash
python grafo.py
```

Esto generará:

1. **Reporte en consola** con nodos, aristas, grados y métricas de centralidad.
2. **Visualización gráfica** de un grafo de ciudades y un árbol binario.
3. **Tiempo de ejecución** de los cálculos de centralidad.

---

## Resultados esperados

* Listado de nodos, aristas y grados.
* Valores de centralidad (grado, cercanía, intermediación).
* Dos gráficos:

  * Grafo con conexiones entre ciudades.
  * Árbol binario balanceado.

---

## Uso de Agente de IA

* **Agente**: ChatGPT (OpenAI).
* **Porcentaje de código generado con ayuda del agente**: 80%.
* El resto del código y pruebas fueron ajustados manualmente.

---

## Análisis de la estructura utilizada

* **Tipo de estructura**: Grafo no dirigido (`nx.Graph`).
* **Ventajas**:

  * Representa relaciones bidireccionales de forma sencilla.
  * NetworkX ofrece funciones para calcular métricas fácilmente.
* **Desventajas**:

  * Puede requerir mucha memoria en grafos muy grandes.
  * La complejidad de cálculo aumenta con el número de nodos.

**Tiempo de ejecución promedio**:
Menos de un segundo para el dataset de prueba.


---

##Autor

**Robert Reyes** – 2025
