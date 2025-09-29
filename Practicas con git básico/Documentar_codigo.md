# 📄 Documentación de Código en Python, JavaScript y PHP

## 🧠 Introducción

La documentación del código es una parte fundamental del desarrollo de software. Nos permite entender cómo funciona una aplicación, facilita el trabajo en equipo y mejora el mantenimiento del código a largo plazo. 

Este documento resume las convenciones y herramientas más comunes para documentar código en **Python**, **JavaScript** y **PHP**.

Algunos editores de código tienen atajos para poder comentar y descomentar según en lenguaje que estes utilizando. Por ejemplo en Visual Studio Code es seleccionando el texto que quieras comentar y el conjunto de teclas **Ctrl+K+C**.

---

## 🐍 Python

Para comentar código en Python tienes dos maneras de hacerlo, ya quieras hacerlo en una sola línea o encerrar el texto en un bloque.

Para comentar una sola linea puedes hacerlo con la almohadilla **#** seguido de lo que quieres comentar.
 
Ejemplo:
```python
# Esto suma dos números
resultado = 5 + 3
```


Para comentar varias lineas del código en Python se debe realizar usando triple comilla simple o doble **"""** o **'''**.

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
Como vemos las dos formas de utilizar son sencillas y dependen mas de la situación, si quieres comentar algo sencillo utilizar **#**, y si tienes que comentar el funcionamiento de una función y los parametros que se deben utilizar utilizar tres comillas dobles o simples **"""**.

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
