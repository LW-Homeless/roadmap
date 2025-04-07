Simple solución para el desafío [Personal Blog](https://roadmap.sh/projects/personal-blog) de [roadmap.sh](https://roadmap.sh)

# Personal Blog
Personal Blog es un proyecto para escribir y publicar artículos sobre diversos temas. Este proyecto tendrá dos secciones: una para invitados y una para administradores.

**Sección de Invitados:** Una lista de páginas a las que cualquier persona puede acceder. 
- Página de inicio: Esta página mostrará la lista de artículos publicados en el blog.
- Página de artículos: Esta página mostrará el contenido del artículo junto con la fecha de publicación.

**Sección de administración:** Son las páginas a las que sólo usted puede acceder para publicar, editar o eliminar artículos.
- Dashboard: Esta página mostrará la lista de artículos publicados en el blog junto con la opción de agregar un nuevo artículo, editar un artículo existente o eliminar un artículo.
- Página para añadir artículo: Esta página contendrá un formulario para agregar un nuevo artículo. El formulario tendrá campos como título, contenido y fecha de publicación.
- Página para editar artículo: Esta página contendrá un formulario para editar un artículo existente. El formulario tendrá campos como título, contenido y fecha de publicación.

# Requerimiento
Python v3.11.3  
Django v5.1.7  
django-ckeditor-5 v0.2.1.7   
pillow v11.1.0  

# Solución
- Lenguaje de Programación: Python 3.11.3.
- Tipo de programación: Programación orientada a objetos (POO).
- Patrón de diseño: Modelo-Vista-Template (MVT).

El patrón de diseño MVT tiene la siguiente estructura.
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/mvc-django.png)

# Cómo utilizar
`pip install -r requirements.txt`  
`python3 manage.py runserver 80`

Nombre de usuario y contraseña de la sección de administración: (admin:admin)

# Captura de pantalla
**Sección de invitados**
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/personal-blog-public1.png)
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/personal-blog-public2.png)
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/personal-blog-public3.png)

**Sección de administración**
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/dashboard-1.png)
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/dashboard2.png)
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/dashboard3.png)
![alt text](https://github.com/LW-Homeless/roadmap/blob/main/backend/Personal-Blog/IMG-README/dashboard4.png)

