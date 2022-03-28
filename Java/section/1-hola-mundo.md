# Hola Mundo 

Lo primero que aprende un programador es a escribir hola mundo. Puede parecer sencillo sin embargo requiere conocer ciertos aspectos de un lenguaje de programación: la estructura básica y el comando para escribir. Luego de eso, el paso más obvio es aprender a leer y almacenar información.

## Programa Java

En el mundo de la programación, un paradigma es una forma de crear los programa. Hay lenguajes multiparadigma (como Python) que implementan varios paradigma y hay leguajes como Java que solo implementan uno. Java implementa el paradigma orientado a objetos en el que todo elemento del programa es un objeto. Sin entrar mucho en detalle, los objecto son contenedores de información y acciones. Además, cada objeto es creado a partir de una **clase**, que es el plano u estructura del objeto.

Para crear un programa en java, debemos crear un archivo con la extensión `.java`, dentro del archivo crearemos una clase **con el mismo nombre del arhivo**

```java
class _nombre_del_archivo_ {
    
}
```

la palabras `class` le indica al lenguaje que crearemos una clase. Seguido, se escribe el nómbre de la clase y, entre corchetes curvos `{}` se escribiran las propiedades de la clase. Si usas algún IDE (Entorno integrado de desarrollo) como intelliJ, VScode o Netbeans, se creara un proyecto con una estrucutra parecida a la siguiente:

```
nombre_del_proyecto
└───src
│   │	nombre_del_proyecto.java
|
...
```

puede que haya mas archivo o menos, pero lo importante es la carpeta src (de source o funte) que contiene el código del proyecto. Por defecto, puede traer un archivo java con el nombre del proyecto o llamado Main. Tambien es posible que se cree otra carpeta dentro del src

```
nombre_del_proyecto
└───src
│   │	nombre_del_proyecto
|	|	└─── nombre_del_proyecto.java
...
```

esa carpeta es un paquete de java. Sirve para orgranizar el código. Si usaremos paquetes, es necesaio poner el nombre del paquete en la declaración de la clase. Por ejemplo:

```java
package _nombre_del_paquete_;

class _nombre_del_archivo_ {
    
}
```

El paquete debe ponerse al comienzo de la clase (antes de crear la clase). Se usa la palabra `package` seguida del nombre dle paquete para indicar el paquete. Y debe finalizar con punto y coma (;). Esto hacer parte de la gramatica de Java: las lineas de código (a exepción de los código de bloque como las clases) deben terminar el punto y coma (;).

Por útlimo, debemos crear el **método main**. Cuando el programa se ejecute, el lenguaje buscara este método y seguira paso a paso lo que este escrito en el:

```java
package _nombre_del_paquete_;

class _nombre_del_archivo_ {
    
    public static void main(String[] args) {
        
    }
    
}
```

## Escribir

Para escribir en java usamos la siguiente instrucción:

```java
System.out.println("ESCRIBE ALGO AQUÍ");
```

:eyes: La 's' de `System`va en mayuscula y el texto que quieras escribir va entre comillas (").

Podemos usar esto para escribir nuestro deseado hola mundo:

```java
class holaMundo {
    
    public static void main(String[] args) {
        System.out.println("Hola Mundo");
    }
}
```

:eyes: En este ejemplo no se coloco el paquete. Si vas a copiar y pegar todo el ejemplo, recuerda poner el paquete.
