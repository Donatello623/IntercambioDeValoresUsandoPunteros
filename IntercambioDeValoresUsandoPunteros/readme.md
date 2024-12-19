# Proyecto de Intercambio de Valores en C++

Este proyecto en C++ demuestra cómo intercambiar los valores de dos variables utilizando punteros. El programa inicializa dos variables con valores enteros, y luego intercambia sus valores usando una función `swap` que toma como parámetros las direcciones de memoria de las variables.

## Descripción

Este proyecto contiene un programa que utiliza punteros para realizar el intercambio de valores entre dos variables. La función `swap` toma dos punteros a enteros, intercambia los valores que apuntan, y luego muestra el resultado antes y después del intercambio en la salida.

El programa sigue estos pasos:
1. Inicializa dos variables `x` y `y` con valores predeterminados.
2. Muestra los valores de las variables antes del intercambio.
3. Llama a la función `swap` para intercambiar los valores de las dos variables.
4. Muestra los valores de las variables después del intercambio.

## Cómo Ejecutarlo

### Requisitos
- Un compilador de C++ (por ejemplo, g++, Clang, etc.).
- Un entorno de desarrollo adecuado para compilar y ejecutar código en C++.

### Instrucciones

1. **Clonar el repositorio** (si el proyecto está en un repositorio Git):
   ```bash
   git clone <URL-del-repositorio>
   cd <nombre-del-directorio>
Compilar el código: Si estás usando g++, ejecuta el siguiente comando en la terminal:

bash
Copiar código
g++ -o intercambio_valores intercambio_valores.cpp
Ejecutar el programa: Una vez compilado, ejecuta el programa con:

bash
Copiar código
./intercambio_valores
El programa mostrará los valores de las variables antes y después de que se realice el intercambio.