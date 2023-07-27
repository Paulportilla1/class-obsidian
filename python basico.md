  |<p>Es un lenguaje de programación fácil de leer que permite asignar de variables, operaciones matemáticas, condiciones y manipulación en la cual  debemos respetar las condiciones  para que al poder ejecutar nos funcione el código en la cual nos muestra la  información de ayuda de la función  en la cual tiene 4 encargados mas importante de la base de datos " date ciense. " date cleaner" etc. </p>
 
==lo importante para python es tener PYCHARM y también lo que es importante es la idexacion

<h1>Ejemplos de pyton básico</h1>

1. Operaciones matemáticas básicas:
```python
# Suma
resultado_suma = 10 + 5
print(resultado_suma)

# Resta
resultado_resta = 20 - 7
print(resultado_resta)

# Multiplicación
resultado_multiplicacion = 4 * 6
print(resultado_multiplicacion)

# División
resultado_division = 15 / 3
print(resultado_division)

# Potencia
resultado_potencia = 2 ** 3
print(resultado_potencia)
```

2. Variables y entrada del usuario

```python
nombre = input("Ingresa tu nombre: ")
print("Hola, " + nombre + "!")

edad = int(input("Ingresa tu edad: "))
año_actual = 2023
año_nacimiento = año_actual - edad
print("Naciste en el año " + str(año_nacimiento) + ".")
```

3. Estructuras de control - condicional 
```python

numero = int(input("Ingresa un número: "))
if numero > 0:
    print("El número es positivo.")
elif numero < 0:
    print("El número es negativo.")
else:
    print("El número es cero.")

hora = int(input("Ingresa la hora actual (formato 24 horas): "))
if hora < 12:
    print("Buenos días!")
elif hora < 18:
    print("Buenas tardes!")
else:
    print("Buenas noches!")
```

<h1>funciones y ayuda</h1>
<p>Es la ayuda integrada los argumentos por defecto, las funciones que no devuelven valores y las funciones de orden superior que se puede utilizan para realizar tareas específicas. Una función toma una o más entradas (argumentos) y puede devolver un resultado (retorno)</p> 
```python
# Definición de una función
def saludar(nombre):
    """
    Esta función imprime un saludo con el nombre proporcionado.
    """
    print("Hola, " + nombre + "!")
# Llamada a la función
nombre_usuario = "Juan"
saludar(nombre_usuario)

help(print)
```

<h1> booleans y condicionales</h1>
<p>python usa bool con valores true/false es se utiliza con operadores booleans, comparaciones y condicionales esto permite el control de la ejecución del código</p>
```python
verdadero = True
falso = False
```

### Operadores de comparación

Los operadores de comparación son utilizados para comparar valores y producir resultados booleanos. Aquí hay algunos ejemplos:

```python
# Igualdad
print(5 == 5)  
print(5 == 10)  

# Desigualdad
print(10 != 5)  
print(10 != 10)  

# Mayor que y menor que
print(8 > 5)  
print(3 < 1)  

# Mayor o igual que y menor o igual que
print(7 >= 5)  
print(3 <= 3)  
```

### Operadores lógicos:

Los operadores lógicos permiten combinar expresiones booleanas. Los principales operadores lógicos en Python son `and`, `or` y `not`.

```python
# Operador and (y)
print(True and True)  
print(True and False)  
print(False and False)  

# Operador or (o)
print(True or True)  
print(True or False)  
print(False or False)  

# Operador not (no)
print(not True) 
print(not False)  
```

### Condicionales en Python:

Los condicionales se utilizan para ejecutar diferentes bloques de código según el resultado de una expresión booleana. El condicional más común es el `if`, pero también puedes usar `elif` (que significa "else if") y `else`.

```python
numero = 10
if numero > 0:
    print("El número es positivo.")
else:
    print("El número es cero o negativo.")
```
 
 <h1>Lista</h1>
<p> son secuencias que pueden ordenar los valores que se puede modificar e indexadas también puede ofrecer funciones útiles para la manipulación</p>
1. Crear una lista:

```python
mi_lista_vacia = []
mi_lista = [1, 2, 3, 4, 5]
```


1. Acceder a elementos de una lista:

```python
mi_lista = [10, 20, 30, 40, 50]
primer_elemento = mi_lista[0]  
ultimo_elemento = mi_lista[-1]  
```


1. Modificar elementos de una lista:

```python
mi_lista = [10, 20, 30, 40, 50]
mi_lista[1] = 25
```
<h1>bucles y compresión de lista</h1>

<p> los bucles en python (for, white) repite codigo determinado las compreciones de listas que permiten conocer los bucles y condicionales en una sola linea </p>

1.bucle, for  **:**  Utilizado para iterar sobre una secuencia (como una lista, tupla, cadena o rango) y realizar acciones en cada elemento.

```python
frutas = ["manzana", "plátano", "naranja"]
for fruta in frutas:
    print(fruta)
``` 
2. bucle, white **:**  Se ejecuta mientras se cumpla una condición específica.

```python
contador = 0
while contador < 5:
    print(contador)
    contador += 1
```

**Comprensión de listas:** 
La comprensión de listas es una forma concisa y elegante de crear listas en Python. Permite generar listas a partir de una expresión y una iteración sobre una secuencia.

```python
cuadrados_pares = [num ** 2 for num in range(10) if num % 2 == 0]
print(cuadrados_pares)  
```

<h1>Strings y diccionarios</h1>

<p> las cadenas son flexibles e inmutables, soportando múltiples métodos. Las listas y diccionarios también son útiles para organizar datos  </p>
## Strings (Cadenas):

Una cadena es una secuencia de caracteres, como texto, que se representa entre comillas (simples o dobles) en Python. 

Ejemplos de cadenas:

```python

cadena_simple = 'Hola, soy una cadena.'
cadena_doble = "¡Yo también soy una cadena!"
```

Las cadenas en Python son inmutables que no se pueden modificar después de su creación que se pueden manipularlas utilizando diferentes métodos 

 operaciones  con cadenas:

```python
saludo = "Hola"
nombre = "Juan"
mensaje = saludo + " " + nombre  


longitud = len(mensaje)  


primer_caracter = mensaje[0]  
ultimo_caracter = mensaje[-1]  


subcadena = mensaje[5:]  
```

## Diccionarios:

Un diccionario en Python es una colección no ordenada de elementos que se almacenan como pares de clave-valor.

Ejemplo de diccionario:

```python
diccionario = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
```

En este ejemplo, "nombre", "edad" y "ciudad" son las claves, y "Juan", 30 y "Madrid" son los valores asociados, respectivamente.

Puedes acceder a los valores de un diccionario 

```python
nombre = diccionario["nombre"]  # Resultado: "Juan"
edad = diccionario["edad"]      # Resultado: 30
```

También puedes agregar, modificar y eliminar elementos del diccionario:

```python
# Agregar un nuevo elemento:
diccionario["profesion"] = "Ingeniero"
# Modificar un valor existente:
diccionario["edad"] = 31
# Eliminar un elemento:
del diccionario["ciudad"]
```

 verificar si una clave está presente en el diccionario se puedes utilizar el operador `in`:

```python
if "nombre" in diccionario:
    print("La clave 'nombre' está presente.")
```
<h1>Trabajando con librerías externas</h1>

<p>python permite la importación de liberáis ya sea estándar o personalizadas a través de importaciones. las librerías de funciones y valores </p>
pip install nombre_libreria
pip install requests

1. **Importar la librería:** 
La forma más común de importar una librería es usar la palabra reservada `import`.

Por ejemplo, si quieres usar la librería "requests" que acabas de instalar, importarías de la siguiente manera:

```python
import requests
```
