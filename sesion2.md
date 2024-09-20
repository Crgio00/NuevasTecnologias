<!-- No borrar o modificar -->

[Inicio](./index.md)

## Semana 3

## Actividad

Actividad que se enfoca en el uso de estructuras de control de iteración y colecciones en Python:

### Título: "Gestor de Biblioteca"

### Objetivo: Practicar el uso de bucles, diccionarios, listas y funciones en Python para crear un sistema simple de gestión de biblioteca.

### Instrucciones:

Crea un diccionario llamado "biblioteca" donde las claves sean los títulos de los libros y los valores sean diccionarios con la siguiente información:
"autor": nombre del autor
"año": año de publicación
"disponible": True si está disponible, False si está prestado
Ejemplo:

```python
biblioteca = {
    "Cien años de soledad": {"autor": "Gabriel García Márquez", "año": 1967, "disponible": True},
    "1984": {"autor": "George Orwell", "año": 1949, "disponible": True},
    "El principito": {"autor": "Antoine de Saint-Exupéry", "año": 1943, "disponible": False}
}
```

1. **Escribe una función llamada "agregar_libro" que permita añadir nuevos libros a la biblioteca. La función debe pedir al usuario el título, autor y año del libro.**

2. **Escribe una función llamada "prestar_libro" que cambie el estado de un libro a no disponible. La función debe pedir al usuario el título del libro.**

3. **Escribe una función llamada "devolver_libro" que cambie el estado de un libro a disponible. La función debe pedir al usuario el título del libro.**

4. **Escribe una función llamada "mostrar_libros" que imprima todos los libros de la biblioteca, incluyendo su información y disponibilidad.**

5. **Crea un menú utilizando un bucle while que permita al usuario realizar las siguientes acciones:**

   - Agregar un nuevo libro
   - Prestar un libro
   - Devolver un libro
   - Ver todos los libros
   - Salir del programa

6. **Implementa el menú de modo que llame a las funciones correspondientes según la opción elegida por el usuario.**

7. **Utiliza un bucle for para mostrar los libros publicados en un año específico que el usuario ingrese.**

Para ver la solucion de click [aqui👈](https://colab.research.google.com/drive/1lMu1GZscQJMWfAo00_wOlMYOPgxZEW4c?usp=sharing)
