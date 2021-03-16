# 2da Clase

## Base10 con numeros irracionales

Detras de las bases esta siempre una suma de potencias y para numeros irracionales, estos los denotaremos con potencias de numeros negativos, ejemplo:

$(35,13)_10 = 3x10^{1} + 5x10^{0} + 1x10^{-1} + 3x10^{-2}$.

Y si quiero pasarlo a un numero de base2? Vamos multiplicando por dos nuestro numero, y luego sustraemos el resultado de nuestro numero anterior hasta llegar a 0 o nuestro numero se repita.

$(0,2)_10 = base2$

$0,2 * 2 = 0,4 => 0,4 - 0 = 0,4$

$0,4 * 2 = 0,8 => 0,8 - 0 = 0,8$

$0,8 * 2 = 1,6 => 1,6 - 1 = 0,6$

$0,6 * 2 = 1,2 => 1,2 - 1 = 0,2$

$(0,2)_10 = (0,011)_2$

## Unidad 2 - Logica proposicional

__Definicion :__ Una proposicion es una oracion a la que puedo asignarle un valor de verdad (verdadero == 1, falso == 0).

Vamos a notar las porposiciones con letras minusculas:  p,q,r,st,u,v,...

n notacion (~) ->  negacion
el o (notacion v) -> disyuncion
el y (notacion ^) -> conjuncion

**observacion** pierdo informacion cuando en la conjuncion p y q son falsas.

Podemos ver estas relaciones en una **tabla de verdades**.

**conjuncion**
|   p   |   q   | p -> q |
| :---: | :---: | :----: |
|   1   |   1   |   1    |
|   1   |   0   |   0    |
|   0   |   1   |   0    |

### Diferencia Simetrica "o exclusivo" /_\

Es una u otra pero nunca ambas a la vez. No exclusivo.

### Equivalencia o doble implicacion <->

Tienen el mismo valor de verdad.

### Implicacion =>

Si p es verdadero entonces q es verdadero. El unico caso en que la implicacion es falso es cuando el antecendente es verdadero y la conjuncion es falso.
