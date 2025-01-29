# INVESTIGACION SOBRE PHP
## ¿Que es PHP?
PHP es un lenguaje de programación para desarrollar aplicaciones y 
crear sitios web que conquista cada día más seguidores. 
Fácil de usar y en constante perfeccionamiento es una 
opción segura para aquellos que desean trabajar en 
proyectos calificados y sin complicaciones.
### Casos de uso
* ***Desarrollo de sitios web dinámicos:*** PHP es ideal para crear sitios web que interactúan con bases de datos y 
generan contenido dinámico. Por ejemplo, blogs, foros, y tiendas en línea.    


* ***Sistemas de gestión de contenido (CMS):*** Muchos CMS populares, como WordPress, Joomla y Drupal, están construidos en PHP.
Estos sistemas permiten a los usuarios crear y gestionar contenido web fácilmente.


* ***Aplicaciones web:*** PHP se utiliza para desarrollar aplicaciones web completas, desde sistemas de gestión 
empresarial hasta plataformas de aprendizaje en línea.


* ***APIs y servicios web:*** PHP puede ser utilizado para crear APIs RESTful que permiten la comunicación entre 
diferentes aplicaciones y servicios.


* ***Automatización de tareas:*** PHP puede ser utilizado para escribir scripts que automatizan tareas repetitivas, 
como la generación de informes, el procesamiento de datos, o la gestión de archivos.


* ***E-commerce:*** Plataformas de comercio electrónico como Magento y WooCommerce (un plugin de WordPress)
están construidas en PHP, facilitando la creación y gestión de tiendas en línea.


* ***Foros y redes sociales:*** PHP es utilizado para desarrollar plataformas de interacción social, 
como foros (por ejemplo, phpBB) y redes sociales.


* ***Gestión de bases de datos:*** PHP se integra fácilmente con bases de datos como MySQL, 
PostgreSQL, y SQLite, permitiendo la creación, lectura, actualización y eliminación de datos de manera eficiente.


### Ventajas
* Aprendizaje intuitivo simplificado
* Código abierto
* Admite una gran cantidad de datos
* Compatibilidad con las principales bases de datos
### Desventajas
* Aprender sobre framework de PHP
* Mala calidad de manejo de errores
* Seguridad baja
* Se necesita un servidor web

## Estructura de Control
### 1. **For:** 
Los bucles for son los más complejos en PHP. Se comportan como sus homólogos en C.
La sintaxis de un bucle for es:

``` php
for (expr1; expr2; expr3) 
sentencia
```

>La primera expresión (expr1) es evaluada (ejecutada) una vez incondicionalmente al comienzo del bucle.
En el comienzo de cada iteración, se evalúa expr2. Si se evalúa como true, el bucle continúa y se ejecutan la/sy sentencia/s anidada/s. Si se evalúa como false, finaliza la ejecución del bucle.
Al final de cada iteración, se evalúa (ejecuta) expr3.

### Ejemplo
``` php
 for ($i = 1; $i <= 10; $i++) { 
   echo $i;
}
```

### 2. **ForEach:** 
El constructor foreach proporciona un modo sencillo de iterar sobre arrays. foreach funciona sólo sobre arrays y objetos, 
y emitirá un error al intentar usarlo con una variable de un tipo diferente de datos o una variable no inicializada.
Existen dos sintaxis:

``` php
foreach (expresión_array as $valor)
 sentencias  
 
foreach (expresión_array as $clave => $valor)
sentencias
```

>La primera forma recorre el array dado por expresión_array. En cada iteración, el valor del elemento actual se asigna a $valor y el puntero interno del array avanza una posición (así en la próxima iteración se estará observando el siguiente elemento).

>La segunda forma además asigna la clave del elemento actual a la variable $clave en cada iteración.

### Ejemplo
``` php
$a = array(1, 2, 3, 17);
foreach ($a as $v) {
echo "Valor actual de \$a: $v.\n";
}
```

### 3. If
El constructor if es una de las características más importantes de muchos lenguajes, incluido PHP. 
Permite la ejecución condicional de fragmentos de código. PHP dispone de una estructura if que es similar a la de C:

``` php
if (expr)
sentencia
```

>Como se describe en la sección sobre expresiones, la expresión es evaluada a su valor booleano. 
Si la expresión se evalúa como true, PHP ejecutará la sentencia y si se evalúa como false la ignorará. 
Más información sobre qué valores evalúan como false se puede encontrar en la sección 'Convirtiendo a booleano'.

### Ejemplo 
``` php
<?php
if ($a > $b) {
  echo "a es mayor que b";
}
?>
```

`INVESTIGACION HECHA POR:`   
`JAVIER ALEJANDRO HERNANDEZ RAMOS`   
`0801200316149`

