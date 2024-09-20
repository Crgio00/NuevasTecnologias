<!-- No borrar o modificar -->

[Inicio](./index.md)

## Semana 4

## Actividad: Gestión de Archivos con Git y GitHub (Python)

## Objetivo

Aprender a utilizar Git y GitHub para gestionar un proyecto de Python, realizando un seguimiento de los cambios en el código y colaborar con otros.

## Pasos

### 1. Configurar el entorno

- **Instalar Git:** Si no lo tienes instalado, descarga e instala Git desde [git-scm.com](https://git-scm.com/).
- **Crear una cuenta en GitHub:** Si no tienes una, crea una cuenta gratuita en [github.com](https://github.com/).
- **Crear un repositorio en GitHub:** Ve a tu perfil de GitHub y crea un nuevo repositorio con el nombre `mi_proyecto_python`. Deja la opción "Initialize this repository with a README" marcada y selecciona "Python" como lenguaje.

### 2. Crear el proyecto en local

- **Clonar el repositorio:** Abre una terminal o línea de comandos y clona el repositorio de GitHub en tu computadora local:

  ```bash
  git clone https://github.com/tu_usuario_github/mi_proyecto_python.git
  ```

  Reemplaza `tu_usuario_github` con tu nombre de usuario en GitHub.

- **Crear el archivo `main.py`:** Dentro de la carpeta `mi_proyecto_python`, crea un archivo llamado `main.py` con el siguiente código:

  ```python
  def saludar(nombre):
      """
      Función que saluda a una persona.

      Args:
          nombre: El nombre de la persona a la que se saluda.

      Returns:
          Un mensaje de saludo.
      """
      return f"¡Hola, {nombre}!"

  if __name__ == "__main__":
      nombre = input("Ingrese su nombre: ")
      saludo = saludar(nombre)
      print(saludo)
  ```

### 3. Comenzar a trabajar con Git

- **Agregar el archivo al repositorio:** Utiliza el comando `git add .` para agregar todos los archivos del proyecto al área de preparación (staging area).
- **Comentar los cambios:** Utiliza el comando `git commit -m "Agregar archivo main.py"` para confirmar los cambios en el repositorio local.
- **Enviar los cambios a GitHub:** Utiliza el comando `git push origin main` para enviar los cambios del repositorio local al repositorio remoto en GitHub.

### 4. Realizar cambios y colaborar

- **Modificar el código:** Realiza cambios en el archivo `main.py`, por ejemplo, agrega una nueva función para despedirse:

  ```python
  def saludar(nombre):
      """
      Función que saluda a una persona.

      Args:
          nombre: El nombre de la persona a la que se saluda.

      Returns:
          Un mensaje de saludo.
      """
      return f"¡Hola, {nombre}!"

  def despedirse(nombre):
      """
      Función que se despide de una persona.

      Args:
          nombre: El nombre de la persona a la que se despide.

      Returns:
          Un mensaje de despedida.
      """
      return f"¡Adiós, {nombre}!"

  if __name__ == "__main__":
      nombre = input("Ingrese su nombre: ")
      saludo = saludar(nombre)
      print(saludo)
      despedida = despedirse(nombre)
      print(despedida)
  ```

- **Comentar y enviar los cambios:** Repite los pasos de agregar, comentar y enviar los cambios a GitHub.

- **Crear una nueva rama:** Utiliza el comando `git checkout -b nueva_caracteristica` para crear una nueva rama para trabajar en una nueva funcionalidad.

- **Trabajar en la nueva rama:** Realiza cambios en el archivo `main.py` en la nueva rama.

- **Comentar y enviar los cambios:** Repite los pasos de agregar, comentar y enviar los cambios a GitHub para la nueva rama.

- **Enviar una solicitud de fusión (pull request):** En GitHub, ve a la sección de "Pull requests" y crea una nueva solicitud para fusionar la rama `nueva_caracteristica` con la rama principal (`main`). Escribe un mensaje explicando los cambios realizados y pide a otro usuario que revise tu código.

- **Fusionar la rama:** Una vez que la solicitud de fusión sea revisada y aprobada, puedes fusionarla con la rama principal en GitHub.

### 5. Trabajar en equipo

- **Invitar a colaboradores:** En GitHub, invita a otros usuarios a colaborar en el repositorio.
- **Clonar el repositorio:** Los colaboradores pueden clonar el repositorio en su computadora local.
- **Trabajar en ramas:** Los colaboradores pueden trabajar en sus propias ramas para desarrollar nuevas funcionalidades o corregir errores.
- **Enviar solicitudes de fusión:** Los colaboradores pueden enviar solicitudes de fusión para integrar sus cambios en la rama principal.
- **Revisar código:** Los colaboradores pueden revisar el código de otros usuarios y proporcionar comentarios.

Esto fue un Fork de la actividad en clase, algo siemple aqui esta el [Link del repositorio](https://github.com/Crgio00/test_fork.git) , sujeto a cambio.
