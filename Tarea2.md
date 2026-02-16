Inicio

1. Leer el código fuente del algoritmo.
2. Identificar las estructuras principales:
      - Bucles (for, while)
      - Bucles anidados
      - Condicionales (if, switch)
      - Llamadas recursivas
3. Determinar el tamaño de entrada (n).
4. Analizar cada estructura:

      4.1 Si hay un solo ciclo que recorre n elementos → O(n)
      4.2 Si hay ciclos anidados → multiplicar complejidades
              Ej: for dentro de for → O(n²)
      4.3 Si el ciclo divide el problema en cada iteración
              Ej: n = n/2 → O(log n)
      4.4 Si hay recursividad:
              - Contar número de llamadas
              - Analizar tamaño del subproblema
5. Eliminar constantes y términos menores.
6. Conservar el término dominante.
7. Expresar resultado en notación Big O.

Fin
