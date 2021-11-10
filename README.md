# PC2: Práctica Calificada 2
**course:** Programación II  
**unit:** 3, 4 y 5  
**cmake project:** prog2_pc2_lab102_v2021_2

## Indicaciones Específicas
- El tiempo límite para la evaluación es 100 minutos.
- Cada pregunta deberá ser respondida en un archivo fuente (`.cpp`) y un archivo cabecera (`.h`) con el número de la pregunta:
  - `p1.cpp, p1.h`
  - `p2.cpp, p2.h`
  - `p3.cpp, p3.h`
- Deberás subir estos archivos directamente a [www.gradescope.com](https://www.gradescope.com) o se puede crear un `.zip` que contenga todos ellos y subirlo.

## Competencias
- Para los alumnos de la carrera de Ciencia de la Computación
  - Aplica conocimientos de computación apropiados para la solución de problemas definidos y sus requerimientos en la disciplina del programa.(nivel 2)
  - Diseña, implementa y evalúa soluciones a problemas complejos de computación.(nivel 2)
  - Crea, selecciona, adapta y aplica técnicas, recursos y herramientas modernas para la práctica de la computación y comprende sus limitaciones.(nivel 2)

- Para los alumnos de las carreras de Ingeniería
  - Capacidad para aplicar conocimientos de matemática.(nivel 2)
  - Capacidad para diseñar un sistema, un componente o un proceso para satisfacer las necesidades deseadas dentro de restricciones realistas(nivel 2)

### Pregunta #1 - Suma de filas y columnas (7 points)

Escribir un programa que utilizando matrices y arreglos dinámicos, lea desde el teclado una matriz de números enteros de tamaño `n x n`, que calcule la suma de cada fila, almacenado los resultados en un arreglo de tamaño `n`, de igual modo realizar el mismo cálculo con las columnas, almacenado también los resultados en un arreglo de tamaño `n`.

Finalmente, el programa debe imprimir la multiplicación de los valores en las posiciones correspondientes de los arreglos generados.

**Ejemplo #1**
#### Input Format
```cpp
3
2 2 2
3 3 3
4 4 4
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
54 81 108
```

**Ejemplo #2**
#### Input Format
```cpp
2
1 1
4 3
```
#### Output Format
```cpp
10 28
```

### Pregunta #2 - Multiplicación del resto (6 points)

Escribir un programa que utilizando vectores, lea desde el teclado un vector de números enteros de tamaño `n`, que reemplace cada valor con el producto del resto de los otros números y muestre los nuevos valores del vector.

**Ejemplo #1**
#### Input Format
```cpp
6
2 3 1 2 3 4
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
72 48 144 72 48 36
```

**Ejemplo #2**
#### Input Format
```cpp
4
1 1 2 2
```
#### Output Format
```cpp
4 4 2 2
```

### Pregunta #3 - Factorización de polinomio (7 points)

Un monomio es una expresión que sigue la siguiente forma: `ax^b` donde: `a` es el coeficiente y `b` el grado.  
Definir una clase que represente un monomio `class monomio_t` y escribir un programa que permita generar un vector de monomios de tamaño `n` que lea el coeficiente y el grado de cada uno de los `n` monomio desde el teclado.
El programa deberá generar un nuevo vector que almacene la factorización de los monomios de modo que solo se almacene un monomio por grado. El resultado debera ser mostrado de modo que los monomios se muestren ordenados de menor grado a mayor grado.

**Ejemplo #1**
#### Input Format
```cpp
5
2 3
1 2
4 3
7 2
4 5
```

#### Constraints
```cpp
No se requiere textos al ingresar valores (std::cout)
```

#### Output Format
```cpp
  8x^2 6x^3 4x^5
```

**Ejemplo #2**
#### Input Format
```cpp
6
10 5
1 1
2 2
3 4
2 1
8 5
```
#### Output Format
```cpp
3x^1 2x^2 3x^4 18x^5
```
