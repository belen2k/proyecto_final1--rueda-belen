Sistema de Gestión de Estudiantes, Profesores y Notas.

Este proyecto es una *aplicación web desarrollada con Django* que permite gestionar *estudiantes, **profesores* y *notas. Se ha creado siguiendo el patrón de diseño ate) de Django, facilitando la organización de la lógica y estructura del código para una administración eficaz de los registros.

La aplicación incluye funcionalidades para agregar, listar y gestionar los registros de profesores, estudiantes y notas.

funciones
Listar Registros
- *Profesores*: Visualiza todos los profesores disponibles con su nombre, apellido y correo electrónico.
- *Estudiantes*: Muestra una lista de estudiantes registrados con su nombre, apellido y correo electrónico.
- *Notas*: Visualiza las notas disponibles, mostrando el nombre de la asignatura, el código y el profesor asignado.

 *Agregar Registros*
- *Profesores*: Permite agregar nuevos profesores a la base de datos.
- *Estudiantes*: Permite agregar nuevos estudiantes y asociarlos con las notas que cursan.
- *Notas*: Permite agregar nuevas notas y asignarlas a un profesor.

Tecnologías Utilizadas

- *Python*
- *Django*
- *SQLite* (base de datos por defecto)
- *Bootstrap 5* (para el diseño de la interfaz)

 Instalación

1. Clona el repositorio
    bash
    git clone https://github.com/belen2k/tercera-preentrega-rueda-belen.git
    
2. Crea y activa un entorno virtual:
    bash
    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    .\venv\Scripts\activate  # Windows
    

3. Instala las dependencias
    bash
    pip install -r requirements.txt
    

4. Ejecuta las migraciones:
    bash
    python manage.py migrate
    

5. Inicia el servidor:
    bash
    python manage.py runserver
    

 Acceso al sitio

Accede al sitio localmente en (http://127.0.0.1:8000/).
