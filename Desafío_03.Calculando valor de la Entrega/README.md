# 🚚 Desafío 03: Calculando el Valor de la Entrega

![Estado](https://img.shields.io/badge/Estado-Completado-success)
![DFD](https://img.shields.io/badge/DFD-1.1-blue)
![Algoritmo](https://img.shields.io/badge/Algoritmo-Lenguaje%20Natural-orange)

## 📖 Descripción

Este proyecto presenta la solución al desafío **"Calculando el Valor de la Entrega"**, cuyo objetivo es diseñar un algoritmo y un diagrama de flujo que permitan calcular el costo final de una entrega en función de la distancia recorrida y las condiciones climáticas.

### 📊 Diagrama de Flujo

![Diagrama de Flujo](docs/diagrama.png)

### ▶️ Ejecución del Algoritmo

![Ejecución del Algoritmo](docs/ejecucion.png)

---

## 🎯 Objetivo

Determinar la tarifa final de entrega aplicando las siguientes reglas:

| Distancia                 | Tarifa Base |
| ------------------------- | ----------- |
| Hasta 5 km                | $5.00       |
| Más de 5 km y hasta 10 km | $8.00       |
| Más de 10 km              | $10.00      |

🌧️ Si el pedido se realiza en un día de lluvia, se añade un recargo de **$2.00** a la tarifa base.

---

## 🔢 Variables Utilizadas

| Variable      | Tipo   | Descripción                                                  |
| ------------- | ------ | ------------------------------------------------------------ |
| tarifa1       | Entero | Tarifa para entregas de hasta 5 km. Valor: 5                 |
| tarifa2       | Entero | Tarifa para entregas de más de 5 km y hasta 10 km. Valor: 8  |
| tarifa3       | Entero | Tarifa para entregas de más de 10 km. Valor: 10              |
| distancia     | Real   | Distancia de la entrega expresada en kilómetros.             |
| tarifa_previa | Real   | Tarifa base calculada según la distancia recorrida.          |
| estado_lluvia | Lógico | Indica si existe lluvia durante la entrega.                  |
| tarifa_final  | Real   | Tarifa total luego de aplicar el posible recargo por lluvia. |

---

## 🧠 Lógica del Algoritmo

1. Solicitar la distancia de la entrega.
2. Evaluar el rango de distancia.
3. Asignar la tarifa correspondiente a `tarifa_previa`.
4. Solicitar el estado de lluvia.
5. Si está lloviendo, sumar $2.00 a la tarifa base.
6. Almacenar el resultado en `tarifa_final`.
7. Mostrar el valor final de la entrega.

---
## 📊 Diagrama de Flujo

El diagrama se encuentra disponible en:

```text
docs/diagrama.png
```

### Vista previa

![Diagrama de Flujo](docs/diagrama.png)

---
## 📂 Estructura del Proyecto

```text
Desafío_03.Calculando valor de la Entrega/
│
├── docs/
│   ├── diagrama.png
│   └── ejecucion.png
│
├── ejemplos/
│   └── caso_prueba.txt
│
├── source/
│   └── Tarifa_Entrega.dfd
│
└── README.md
```

### 📁 Descripción de Carpetas y Archivos

| Elemento              | Descripción                                             |
| --------------------- | ------------------------------------------------------- |
| 📂 docs               | Contiene las evidencias gráficas del proyecto.          |
| 🖼️ diagrama.png      | Imagen del diagrama de flujo desarrollado.              |
| 🖼️ ejecucion.png     | Captura de la ejecución o prueba del algoritmo.         |
| 📂 ejemplos           | Contiene los casos de prueba del proyecto.              |
| 📄 caso_prueba.txt    | Entradas y salidas esperadas para validar el algoritmo. |
| 📂 source             | Contiene el archivo fuente del diagrama de flujo.       |
| 📄 Tarifa_Entrega.dfd | Archivo DFD 1.1 con la solución desarrollada.           |
| 📄 README.md          | Documentación general del proyecto.                     |

---

## 🧪 Caso de Prueba

### Entrada

```text
Ingrese distancia: 12
¿Está lloviendo?: Sí
```

### Proceso

```text
tarifa_previa = tarifa3 = 10
tarifa_final = 10 + 2
```

### Salida

```text
Valor de Entrega Final es: $12
```

---

## 🛠️ Herramientas Utilizadas

* 📊 DFD 1.1
* 📝 Algoritmos en Lenguaje Natural
* 🌳 Git
* 🐙 GitHub

---

## 📚 Competencias Desarrolladas

* ✔️ Análisis de problemas.
* ✔️ Diseño de algoritmos.
* ✔️ Uso de estructuras condicionales.
* ✔️ Elaboración de diagramas de flujo.
* ✔️ Modelado lógico de procesos.
* ✔️ Control de versiones con Git y GitHub.

---

## 👨‍💻 Autor

Proyecto desarrollado como práctica académica para el aprendizaje de **Algoritmos y Diagramas de Flujo (DFD 1.1)**.

---

⭐ Si este proyecto te resulta útil, considera darle una estrella al repositorio.
