# Minuta de la sesión 2 de requisitado — FUNIBER

## 1. Información general

- **Fecha:** Miércoles 25 de noviembre de 2026
- **Hora de inicio:** 9:00 am
- **Cliente:** Lucía Terán.
- **Equipo:** Jaime Lomo, Pablo Fernández, Leslie Romero, Ricardo Rubio, Vanessa Pak y Bernardo Zablah.
- **Objetivo de la sesión:** Aclarar las dudas pendientes de la primera sesión y plantear una propuesta de solución.

## 2. Contexto de la sesión

La sesión se dedicó a resolver las cuestiones que quedaron abiertas en la sesión 1 y a contrastar con el cliente la propuesta de solución basada en un **gestor web**. Se trataron la organización actual de los contenidos, las diferencias entre países, los usuarios del gestor y la estructura de directorios, componentes y vistas.

## 3. Aclaraciones sobre la situación actual

###  Contenido y oferta académica

- El contenido es el mismo en todos los países; solo cambia el término. El único caso distinto es España.
- La oferta académica es la misma en todos los países; solo se traduce.

###  Obra cultural

- La obra cultural no tiene por qué estar replicada en todos los directorios; al igual que el resto del contenido, solo se traduce.
- La entidad sería la **obra cultural**, que crea eventos y genera noticias (sugerencia de Masías).
- La obra cultural es un evento que, como tal, va fuera de la web de FUNIBER: es otra web que se presenta.

### Investigación

FUNIBER financia la investigación en general y, a partir de ella, se producen proyectos y artículos.

### Publicaciones y estados

- Para las publicaciones no existe un flujo complicado: se guardan como borrador (es decir, sin publicar) o se publican directamente.
- Hay dos estados: **publicado** y **no publicado**.
- La publicación es todo lo que es visible en la web. Se señaló que se están mezclando los tipos de contenido con el estado en el que acaban.
- Una noticia y un artículo son un tipo de publicación, pero no derivan necesariamente en publicaciones. Lo mismo ocurre con la actividad (sustentan noticias).

### Captación de alumnos y formularios

- La forma en que una persona llega a ser alumna es a través de la página de inicio (home) de FUNIBER, donde están los formularios para mostrar interés y solicitar información.
- La página de inicio, las áreas y los programas tienen el mismo formulario; los eventos tienen información diferente. Los formularios funcionarían como atributos.

### Webinars

- El webinar es una posible actividad.
- Los webinars también tienen formulario.

## 4. Particularidades de cada país

- El apartado **Quiénes somos** cambia en Colombia y Argentina por particularidades legales.
- Hay áreas que no se muestran en todos los países, como las licenciaturas y los grados. Si un país no tiene grado o licenciatura, sus subdirectorios no se muestran. Se debe definir la posibilidad de mostrar contenido dependiendo del país.
- Cada país tiene un idioma por defecto, que funciona como atributo del país.

## 5. Propuesta de solución: gestor web

### Usuarios y roles

- El gestor lo usan las personas que mantienen la web, es decir, el personal técnico: **desarrolladores**, **administradores** y **editores**.
- Se sugirió que el editor "edita" el componente y su contenido. Debería ser: el **administrador** edita el componente y el **editor** cambia el contenido.
- El administrador:
    - Crea los subdirectorios como tal.
    - Crea los idiomas a nivel de gestor, que pueden estar vinculados a un país, o puede crear el país directamente.
    - Crea más subdirectorios cuando la organización crea áreas nuevas. Esto es necesario para determinadas nomenclaturas: si todos los nombres fueran iguales, el contenido funcionaría igual para todo.

### Estructura de directorios

- No existe un directorio de la organización como tal, solo las sedes.
- Para Lucía, los **directorios** serían las sedes internas, y los **subdirectorios** serían los apartados internos dentro de ellas, como los másteres por área.
- El **directorio raíz** es el contenido de la organización sobre el que impactaría Drupal.

### Componentes y vistas

- En FUNIBER, las **vistas** son plantillas que se usan para establecer la estructura correspondiente a un contenido. Muchos componentes forman una vista.
- Un **componente** puede ser el contacto, pero no todos los componentes contienen contacto; lo principal serían los formularios.
- Deberían existir varios tipos de componentes para que se estructuren de manera correcta en el directorio correspondiente.

### Idiomas

El idioma sería externo a la plantilla y estaría más vinculado al país.

### Historial de versiones

El gestor puede volver a versiones anteriores para restaurar contenido. Se mantiene un histórico de versiones de todo.

### Intereses del cliente en el gestor

- **Apartado de profesores:** los profesores están "quemados" (incluidos de forma fija) en los cinco másteres, por ejemplo, y no hay ningún directorio que facilite su búsqueda.

## 6. Vocabulario del dominio

A partir de los términos recogidos durante la sesión, se amplía el glosario de la sesión 1:

| Término | Significado provisional |
|---|---|
| Gestor web | Herramienta que usa el personal técnico para mantener la web. |
| Desarrollador | Persona del personal técnico que usa el gestor web. |
| Administrador | Usuario del gestor que edita los componentes y crea subdirectorios, idiomas y países. |
| Editor | Usuario del gestor que cambia el contenido. |
| Directorio | Para el cliente, cada una de las sedes internas. |
| Subdirectorio | Apartado interno dentro de un directorio, como los másteres por área. |
| Directorio raíz | Contenido de la organización sobre el que impactaría Drupal. |
| Área | Agrupación de la oferta académica; al crear áreas nuevas se crean subdirectorios. |
| Vista | Plantilla que establece la estructura de un contenido; está formada por muchos componentes. |
| Componente | Parte de una vista, como un formulario o el contacto. |
| Formulario | Componente para mostrar interés y solicitar información. |
| Publicación | Todo lo que es visible en la web. |
| Borrador | Contenido guardado sin publicar. |
| Estado | Situación de una publicación: publicado o no publicado. |
| Obra cultural | Evento que crea eventos y genera noticias; se presenta en una web distinta de la de FUNIBER. |
| Webinar | Posible tipo de actividad; tiene formulario. |
| Idioma por defecto | Idioma principal de cada país; atributo del país. |


## 7. Dudas y cuestiones pendientes

1. Revisar la nomenclatura.
2. Definir la posibilidad de mostrar contenido y subdirectorios dependiendo del país.
3. Confirmar el webinar como tipo de actividad.
