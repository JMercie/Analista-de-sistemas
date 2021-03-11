# 1ra Clase

## Metodologia

Los trabajos practicos se hacen en equipos de max 4 personas.
El primer examen, se recupera con el segundo, y el segundo se recupera en fecha de primeros finales.
La materia no es promocionable
Si se obtiene 7 o mas en ambos parciales, se rinde un multiple choice como examen final.

**Temario**

: Programacion estructurada, POO y colecciones de objetos.


Usaremos Java para la cursada y el runtime sera Java 8. 
El IDE por defecto a usar sera Eclipse, por temas de uniformidad con los profesores.


## Cronograma

- La segunda semana de abril (tentativo) primer examen.
- La segunda semana de junio (tentativo) segundo examen.

**La cursada termina el 30 de junio.**

---

## Java

### Caracteristicas

Iniciativa de Sun Microsystems en 1991

- Simple
- Orientado a objetos
- Distribuido
- Robusto
- Seguro
- Independiente de la plataforma

### JVM

java virtual machine, esta es dependiente del OS en el que se esta ejecutando y es el interprete de java.

![Java Tree](taller_de_programacion_1/imagenes/java_tree.png)

### Clases

Cada programa es una clase, estas se agrupan en paquetes y estos son los que contiene un proyecto.

![Java Structure](taller_de_programacion_1/imagenes/estructura_java.png)

### Variables

: Direccion de memoria vacia, la cual puede variar. Esta apunta a un valor en memoria.


Al java ser un lenguaje fuertemente tipado, las variables deben declararse con sus tipos al iniciarlizarla.

- *Java es caseSensitive*.

Ejemplo practico: 


```java
package example;

public class example1 {

	public static void main(String[] args) {
		System.out.println("Hola mundo"); // prints Hola mundo
		
		int num1;  // initialize a variable
		int num2;
		
		num1 = 3;  //  Expression
		num2 = 1;
		
		int res = num1 + num2;  // statement
		
		System.out.println(res); // prints 4
	}

}
```

#### Sintaxis

Puede usarse el castellano para nombrarlas, pero el nombre **NO** puede:

- empezar con un numero
- contener espacios
- contener acentos
- contener caracteres especiales
- utilizar palabras reservadas del lenguaje

#### Tipos

- primitivos:
    1. int
    2. double
    3. char
    4. String
    5. boolean


```java
int numero = 1;
String cadenaDeCaracteres = "hola mundo";
double decimal = 1.0000001;
char letra = 'l';
boolean verdadero = true;
boolean falso = false;
```

Ejemplo practico, tomaremos input del usuario.

```java
package example;

import java.util.Scanner;

public class example1{
    
    public static Scanner input = new Scanner(System.in);

    public static void() {
        System.out.println("Ingrese su nombre");
        String nombre = input.nextLine();
        input.close();
        System.out.println("Hola " + nombre);
    }
}
```

### Constantes

Tienen un valor fijo durante todo el proceso de ejecucion y se declaran a nivel global dentro de la clase.
Se les debe anteponer el modificador `public static final` , por convencion se escriben en mayuscula y se separan con guion bajo (_).

### Operadores de comparacion

Devuelven booleanos

- igualdad
: num1 == num2
- desigualdad
: num1 != num2
- mayor que
: num1 > num2
- menor que
: num1 < num2
- mayor o igual que
: num1 >= num2
- menor o igual que
: num1 <= num2

### String class

Se declaran de la siguiente forma.

`String saludo = "Hola mundo"`

El operador para unirlas es  '+' 

__*Ejemplo:*__

```java
String cad1 = "Hola";
String cad2 = "Chao";
String cad3 = cad1 + '' + cad2;
```
Para comparar Strings usaremos el metodo 'equals()', caso contrario usaremos '!' al inicio del statement Ejemplo:


```java
String cad1 = "Hola";
String cad2 = "Chao";
boolean result = !cad1.equals(cad2); // prints true
```

### Operadores Booleanos

- AND: &&
- OR: ||
- NOT: !
