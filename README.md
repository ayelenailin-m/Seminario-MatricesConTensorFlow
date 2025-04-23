# Proyecto: Suma y Multiplicación de Matrices con TensorFlow.js

Este proyecto consiste en una aplicación web desarrollada con HTML, JavaScript y Node.js que permite generar matrices aleatorias, sumarlas y multiplicarlas utilizando la librería **TensorFlow.js**.

## ¿Qué hace la aplicación?

- El usuario **solo define las dimensiones** de las matrices.
- Los **valores se generan automáticamente** con números aleatorios entre 1 y 20.
- Se pueden realizar operaciones de:
  - **Suma** de matrices (elemento a elemento).
  - **Multiplicación** de matrices (regla fila × columna).

## Tecnologías usadas

- HTML / CSS / JavaScript
- Node.js
- **[TensorFlow.js](https://www.tensorflow.org/js)** (usando la CDN oficial)

## Funcionalidades de TensorFlow utilizadas

1. `tf.randomUniform([filas, columnas], 1, 21, 'int32')`
   - Genera una matriz aleatoria de números enteros entre 1 y 20.

2. `.add()`
   - Suma dos matrices de igual dimensión, elemento por elemento.

3. `.matMul()`
   - Multiplica dos matrices compatibles según la regla fila × columna.

4. `.array()`
   - Convierte un tensor (matriz de TensorFlow) a una matriz de JavaScript común para mostrar en pantalla.

## Cómo ejecutar

1. Cloná o descargá este proyecto.
2. Asegurate de tener Node.js instalado.
3. Desde la terminal, ejecutá:
   ```bash
   node server.js
   ```
4. Abrí tu navegador en `http://localhost:3000`.

## Autora

Desarrollado por Ailin Ayelen Miño como parte de una tarea de la materia Seminario de Actualización II.