# Operadores

## Objetivo del segundo momento:
El segundo momento didáctico, tiene como finalidad describir los conceptos, tipos de operadores y expresiones
e indicar la importancia del pensamiento computacional, la utilidad en fórmulas dentro de un algoritmo y las
comparaciones, así como agrupar elementos.

Los operadores con los que trabajaremos son de 3 tipos principalmentes y son:

1. Aritméticos
2. Relacionales
3. Lógicos

### Operadores Aritméticos

Son los operadores que se utilizan en operaciones matemáticas.

| Jerarquía     | Operador |
| ---      | ---       |
| 0 | () |
| 1 | ^ |
| 2 | *, / |
| 3 | modulo |
| 4 | +, - |

#### Ejemplo

```
1. x = (3^2 + 10/2) + (3 * 9mod 4 - 1)
   x = (9 + 5) + (27mod4 - 1)
   x = 14 + (3-1)
   x = 14 + 2
   x = 16
```

### Operadores Relacionales

Estos operadores cumplen la función de comparar dos sentencias y el resultado es un valor booleano, o sea que tiene uno de dos posibles valores: 0, 1 ó False y True.

| Operador | Operación |
| ---      | ---       |
| > | Mayor a |
| < | Menor a |
| <= | Menor igual a |
| >= | Mayor igual a |
| <> ó != | Diferente a |
| = | Igual a |

#### Ejemplo

```
1. C > D, E < F, G < E, D > F
   -> REsultado: C > D > F > E > G.
```

### Operadores Lógicos



| Operador | Operación |
| ---      | ---       |
| && | Conjunción |
| || | Disyunción |
| ¬ | Negación |

#### Ejemplo

```
1. ¬(128 < 145 && 12 > 9)
   ¬(   V      &&   V   )
   ¬( V )
   F
```
