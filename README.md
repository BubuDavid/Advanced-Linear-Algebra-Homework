# Implementación del método de Gauss y Gauss-Jordan en Python

## Instrucciones:
- Escriba por favor, en un archivo llamado `matrix.txt`, los sistemas lineales o matrices a resolver, cada fila separada por un salto de línea y cada columna separada con espacios, además, cada sistema lineal (O matriz) separados por dos saltos de línea, a continuación un ejemplo:

```python
1 -1 1 7
1 1 -3 1
2 1 -4 5

2 -5 3 4
1 -2 1 3
5 1 7 11

1 -2 1 13
3 -4 2 1
2 -2 1 0
```
- Corra por favor, todas las celdas, note que las celdas que dan la respuesta están justo debajo de los títulos _"Ejecutar código Gauss"_ y _"Ejecutar código Gauss-Jordan"_

- Se crearán dos archivos llamados: `matrix_gauss_solutions.txt` y `matrix_gauss_jordan_solutions.txt` en donde se podrán encontrar las soluciones a los sistemas con el método de Gauss y con el método de Gauss-Jordan, de igual forma las soluciones apareceran en el output de la celda o en la línea de comandos, depende de donde se ejecute el código.

## Consideraciones:
Solo funciona con Sistemas Lineales cuadrados, es decir, aquellos que tienen dimension nxn+1 (El +1 viene de que estamos suponiendo que la matriz tiene la forma A*=(A|B))

