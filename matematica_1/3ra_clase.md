# 3ra clase

## Resolucion ejercicios TP2

- Ejercicio 8:
    1. a
       - p = falso
       - t = verdadero
       - q
       - r
       - s
    2. b
       - p =  verdadero
       - t =  falso
       - q = falso
       - s = verdadero
    3. c
       - p
       - t
       - q
       - r
       - s

- Ejercicio 9
    1. a
        - p =
    2. b
        - p =

- Ejercicio 10
    1. p => q
    2. r <=> s
    3. ~(t ^ s)
    4. u -> ~ q
    5. u v w
    6. ~(~t)
    7. ~r => ~w

    **tabla de verdad**

    | letra | valor |
    | :---: | :---- |
    |   t   | 1     |
    |   s   | 0     |
    |   r   | 0     |
    |   w   | 0     |
    |   w   | 0     |
    |   u   | 1     |
    |   q   | 0     |
    |   p   | 0     |

## Ley Modus Ponens

$p  = verdadero$

$p => q = verdadero$

### Entonces

$q = verdadero$

## Ley Modus Tolens

$-q  = verdadero$

$p => q = verdadero$

### Entonces

$-p = verdadero$

## Ley Transitividad de la implicacion (silogismo hipotetico)

$p => q =  verdadero$

$q => r = verdadero$

### Entonces

$p => r = verdadero$


## Ley silogismo disyuntivo

$-q =  verdadero$

$p v q = verdadero$

### Entonces

$p= verdadero$

## Contrareciproco

$p=>q = -q => -p$

tabla de verdad

|   p   |   q   | p => q | -q => -p |
| :---: | :---: | :----: | :------: |
|   1   |   1   |   1    |    1     |
|   1   |   0   |   0    |    0     |
|   0   |   1   |   1    |    1     |
|   0   |   0   |   1    |    1     |

## Involucion

$-(p) = p$  Verdadero

## Razonamiento o Teorema

Esta compuesto por un conjunto de hipotesis(proposicion) o tesis(proposicion).

Decimos que el teorema o razonamiento es valido si cuando asumimos que todas las hipotesis son verdaderas podemos concluirque tambien lo es la tesis.

### notacion

- h1
- h2
- h3
- .
- .
- .
- hn

**Entonces** Tesis es verdadera.

**ejemplo:**

$p$ Verdadero

$p=>q$ Verdadero

$q=>r$ verdadero

Entonces **r es verdadero.**