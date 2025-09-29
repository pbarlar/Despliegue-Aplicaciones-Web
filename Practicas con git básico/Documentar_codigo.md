# 📄 Documentación de Código en Python, JavaScript y PHP

## 🧠 Introducción

La documentación del código es una parte fundamental del desarrollo de software. Nos permite entender cómo funciona una aplicación, facilita el trabajo en equipo y mejora el mantenimiento del código a largo plazo. 

Este documento resume las convenciones y herramientas más comunes para documentar código en **Python**, **JavaScript** y **PHP**.

Algunos editores de código tienen atajos para poder comentar y descomentar según en lenguaje que estes utilizando. Por ejemplo en Visual Studio Code es seleccionando el texto que quieras comentar y el conjunto de teclas **Ctrl+K+C**.

---

## 🐍 Python

Para comentar código en Python tienes dos maneras de hacerlo, ya quieras hacerlo en una sola línea o encerrar el texto en un bloque.

Para comentar una sola línea puedes hacerlo con la almohadilla **#** seguido de lo que quieres comentar.
 
Ejemplo:
```python
# Esto suma dos números
resultado = 5 + 3
```


Para comentar varias líneas del código en Python se debe realizar usando triple comilla simple o doble **"""** o **'''**.

Ejemplo: 
```python
def saludar(nombre):
    """
    Devuelve un saludo personalizado para el nombre dado.

    Parámetros:
    nombre (str): Nombre de la persona a saludar.

    Retorna:
    str: Saludo personalizado.
    """
    return f"Hola, {nombre}!"
``` 
Como vemos las dos formas de utilizar son sencillas y dependen mas de la situación, si quieres comentar algo sencillo utilizar **#**, y si tienes que comentar el funcionamiento de una función y los parametros que se deben usar utilizar tres comillas dobles o simples **"""**.

--- 

## 🌐 JavaScript
Para comentar código en JavaScript también existen dos formas: comentarios de una sola línea y comentarios en bloque de varias líneas.

Para comentar una sola línea se utiliza el doble barra lateral **//** seguido del texto que quieres comentar.

Ejemplo:
```javascript
// Esto suma dos números
let resultado = 5 + 3;
```

Para comentar varias líneas en JavaScript se utiliza el símbolo **/\***
 para abrir el comentario y **\*/** para cerrarlo. Es útil cuando quieres comentar un bloque de texto más largo o incluso varias líneas de código.

Ejemplo:
```javascript
/**
 * Esta función recibe dos números y devuelve la suma.
 * Es útil para operaciones básicas de cálculo.
 */
function sumar(a, b) {
    return a + b;
}
```

También se puede usar este formato en una sola línea si se prefiere:
```javascript
/* Esto es un comentario corto en una sola línea */
```

---

## 🐘 PHP
En PHP también se puede comentar en una sola línea o en varias líneas, y las formas son muy parecidas a las de JavaScript y C.

Para comentar una sola línea puedes utilizar **//** o **#**.

Ejemplo:
```php
// Esto suma dos números
# También puedes usar este estilo
$resultado = 5 + 3;
```

Para comentar varias líneas, puedes usar **\*/ ... \*/**, igual que en JavaScript.

Ejemplo:
```php
/**
 * Esta función suma dos valores.
 *
 * @param int $a El primer número
 * @param int $b El segundo número
 * @return int El resultado de la suma
 */
function sumar($a, $b) {
    return $a + $b;
}
```
Este tipo de comentarios en bloque es muy utilizado en PHP para documentar funciones y clases, especialmente con el estándar PHPDoc, que permite generar documentación automáticamente.

Como vemos, PHP ofrece varias formas de comentar, y la elección depende de si necesitas hacer un comentario breve o documentar bien una función.

---

## ✅ Conclusión

Comentar el código correctamente es una práctica esencial en cualquier lenguaje de programación. Ya sea en **Python**, **JavaScript** o **PHP**, existen formas sencillas y estandarizadas de añadir comentarios que mejoran la legibilidad, la colaboración en equipo y el mantenimiento del código a lo largo del tiempo.

Documentar bien el código no es solo una buena práctica, es una parte fundamental del desarrollo de software de calidad.
