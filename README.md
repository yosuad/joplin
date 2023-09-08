<div align="center">
<h1 align="center">Docker Compose de Joplin</h1>    
</div>

<p align="center">
A continuación, les proporciono un archivo de Docker Compose que les permitirá instalar y ejecutar Joplin <br>
en su propio entorno de Docker. Con esta configuración, podrán disfrutar de la versatilidad de Joplin de manera rápida y sencilla en sus propios sistemas</p>
<br>
</br>

## Que es Joplin

Joplin es una aplicación de software de código abierto diseñada para la toma de notas, la organización de información y la gestión de tareas. <br>
Se destaca por su enfoque en la privacidad y la seguridad, así como por su capacidad para funcionar en múltiples plataformas, <br>
lo que la hace muy popular entre aquellos que buscan una alternativa de código 
abierto a aplicaciones comerciales como Evernote o Microsoft OneNote.
<br>
<br>
<br>
<br>

### A continuación, se describen algunas de las características clave de Joplin:

1. Plataformas múltiples: Joplin está disponible para Windows, macOS, Linux, Android e iOS, lo que permite a los usuarios acceder y sincronizar sus notas en una variedad de dispositivos.

2. Sincronización: La aplicación permite la sincronización de notas y datos a través de servicios en la nube como Dropbox, OneDrive, Nextcloud, WebDAV, y otros, lo que facilita el acceso a las notas desde cualquier lugar.

3. Editor de Markdown: Joplin utiliza el formato Markdown para la creación y edición de notas, lo que proporciona un entorno de escritura sencillo y estructurado. Los usuarios pueden agregar formato, enlaces, imágenes y más utilizando Markdown.

4. Cifrado de extremo a extremo: Una característica destacada de Joplin es su enfoque en la privacidad y la seguridad. Ofrece cifrado de extremo a extremo para proteger las notas y garantizar que solo el usuario pueda acceder a su contenido.

5. Gestión de tareas: Joplin incluye funciones de gestión de tareas, lo que permite a los usuarios crear listas de tareas pendientes y asignar prioridades y fechas de vencimiento a las tareas.

6. Etiquetas y carpetas: Los usuarios pueden organizar sus notas utilizando etiquetas y carpetas, lo que facilita la búsqueda y la navegación a través de grandes colecciones de notas.

7. Búsqueda avanzada: La aplicación ofrece capacidades de búsqueda avanzada, lo que permite a los usuarios encontrar notas rápidamente utilizando palabras clave y filtros.

8. Extensiones y complementos: Joplin admite extensiones y complementos que permiten a los usuarios personalizar aún más su experiencia y agregar funcionalidades adicionales.

9. Exportación e importación: Los usuarios pueden exportar sus datos en varios formatos, como PDF o Markdown, y también importar datos desde otras aplicaciones de toma de notas.

10. Interfaz de usuario personalizable: Joplin ofrece opciones de personalización de la interfaz de usuario, lo que permite a los usuarios ajustar la apariencia de la aplicación según sus preferencias.
<br>
<br>
<br>
<br>

En resumen, Joplin es una aplicación de toma de notas de código abierto versátil y segura que ofrece una amplia gama de características para ayudar a los usuarios a organizar y acceder a sus notas y tareas de manera eficiente, mientras se centra en la privacidad y la seguridad. Su capacidad para funcionar en múltiples plataformas y su enfoque en el cifrado de extremo a extremo la convierten en una opción popular para aquellos que buscan una alternativa de código abierto a otras aplicaciones de toma de notas más conocidas.


<br>
<br>
<br>
<br>
<br>

## Instalación
1. clonar el repositorio
```
git clone https://github.com/yosuad/joplin.git
```

<br>


2. ingresamos 
```
cd joplin
```

<br>


3. editar el docker-compose.yaml
    - Borrar paréntesis y signo del dólar, remplazar con la IP y el puerto
  <p align="left"><img src="https://github.com/yosuad/joplin/blob/master/img/setting.png?raw=true"></p>

```
- APP_BASE_URL=http://192.168.1.1:8200
```

<br>


4. inicializar y crear los contenedores
```
docker-compose up -d
```

<br>


5. ingresar en el navegador a la url que se asigo con anterioridad.

<br>


6. login defaul

| email  | password |
| ------------- | ------------- |
| admin@localhost  | admin  |
