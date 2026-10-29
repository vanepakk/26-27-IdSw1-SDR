# Minuta de la sesión 1 de requisitado — FUNIBER

## 1. Información general

- **Fecha:** 26 de octubre de 2026.
- **Hora de inicio:** 14:15 h.
- **Cliente:** Lucía Terán.
- **Equipo:** Jaime Lomo, Pablo Fernández, Leslie Romero, Ricardo Rubio, Vanessa Pak y Bernardo Zablah.
- **Objetivo de la sesión:** Realizar un primer acercamiento al problema del cliente, familiarizarse con su contexto y comprender las necesidades relacionadas.
## 2. Contexto del proyecto

Durante la sesión se presentó la situación del cliente y las dificultades relacionadas con la organización estructural y el mantenimiento de su web.

FUNIBER (pagina del cliente) trabaja en ámbitos relacionados con las becas, los programas de máster y la formación universitaria. Su actividad tiene presencia en diferentes países, por lo que es necesario tener en cuenta las diferencias de terminología, organización y legislación de cada territorio.

Uno de los aspectos señalados durante la sesión fue la dificultad que supone trabajar con una web que se considera demasiado rígida. Se mencionaron tecnologías y herramientas relacionadas con su desarrollo, entre ellas Drupal, Astro y React. Será necesario confirmar cómo se utilizan actualmente y qué limitaciones concretas encuentra el cliente.

## 3. Problema identificado

El problema principal señalado está relacionado con la rigidez de la web de FUNIBER y las dificultades que esto puede ocasionar a la hora de organizar y gestionar sus contenidos.

Actualmente la pagina, debido a su rigidez, no le permite al cliente realizar de manera efectiva y mantenible cambios visuales y estructurales. La idea planteada por el cliente es mantener DRUPAL como cerebro principal, ademas de unificar los diferentes dominios de todos los paises en los cuales esta presente FUNIBER, que derivan de la pagina principal.

El problema estructural radica en que FUNIBER contiene paginas con diferentes dominios (Ejemplo: funiber.org  funiber.es  funiber.pt), lo cual genera una competencia en el "posicionamiento SEO". Esto es un problema a nivel de marketing y visibilidad. El requerimiento del cliente es unificar los dominios a uno principal (funiber.org), y a traves de DRUPAL crear directorios con los diferentes paises, al mismo tiempo que se genera un redireccion interna. Asi logrando que aunque el trafico proviene de varios paises, este sea considerado a un mismo dominio.

La web debe contemplar diferentes tipos de información y adaptarse a las particularidades de los países en los que opera la organización. Esto implica gestionar contenidos relacionados con la formación, las becas, la investigación, las universidades y otras actividades.

Además, es necesario distinguir entre las denominaciones que reciben los programas formativos en los distintos países. Un mismo tipo de programa puede recibir nombres diferentes, como *máster*, *maestría* o *magíster*, según el contexto en el que se utilice.


## 4. Organización y contenidos de la web

Durante la sesión se identificaron diferentes apartados y tipos de contenido que forman parte de la web de FUNIBER o que se consideran relevantes para su organización.

### 4.1. Formación y programas académicos

Se mencionaron los siguientes elementos:

- Programas de máster y otras titulaciones.
- Becas relacionadas con la formación.
- Diferentes denominaciones de los programas académicos según el país.
- Diferencias entre los programas equivalentes a los másteres en España y los utilizados en otros territorios.

Será necesario identificar cómo se clasifican actualmente estos programas y qué diferencias deben tenerse en cuenta para cada país.

### 4.2. Investigación y publicaciones

Se señalaron contenidos relacionados con la actividad investigadora de la organización:

- Un apartado de investigación.
- Información sobre proyectos creados.
- Publicaciones y artículos científicos.

### 4.3. Universidades y convenios

Se mencionó un apartado dedicado a las universidades y los convenios, así como a las organizaciones de los diferentes países.

Queda pendiente conocer cómo se clasifican estas instituciones y qué información se necesita mostrar sobre cada una de ellas.

### 4.4. Actividades y eventos

Se identificaron contenidos destinados a promocionar actividades como exposiciones y conciertos.

Será necesario confirmar qué tipos de eventos se publican, cómo se gestionan y si su organización varía según el país.

### 4.5. Becas

Las becas constituyen otro de los apartados relevantes de la web. Se deberá aclarar cómo se presentan, qué información contiene cada una y qué diferencias existen entre países o programas.

### 4.6. Contacto e información institucional

También se mencionaron apartados relacionados con el contacto y la presentación de la organización, como la información sobre quiénes somos.

### 4.7. Idiomas

Durante la sesión se mencionaron los siguientes idiomas para los contenidos de la web:

- Español.
- Francés.
- Chino.
- Portugués.
- Ingles.
- Italiano.

Será necesario confirmar si todos los apartados están disponibles en todos los idiomas y cómo se gestionan las posibles diferencias entre las versiones lingüísticas.

## 5. Particularidades de cada país

Uno de los aspectos relevantes de la sesión fue la necesidad de considerar las diferencias entre los países en los que FUNIBER desarrolla su actividad.

Se señaló que cada país puede tener su propia terminología y sus particularidades legales. Como ejemplo, se mencionó Brasil en relación con las diferencias que deben tenerse en cuenta.

La terminología académica es especialmente importante, ya que una misma formación puede recibir distintas denominaciones según el país. Por este motivo, no debe asumirse que los términos utilizados en España son equivalentes a los de otros territorios sin comprobarlo previamente.

También se mencionó la existencia de dominios o direcciones web asociados a diferentes países y la necesidad de comprender cómo se relacionan entre sí.

Queda pendiente concretar qué diferencias existen entre las versiones nacionales de la web, cómo se organizan sus contenidos y qué elementos son comunes o específicos de cada país.

## 6. Aspectos técnicos mencionados

Durante la sesión se hicieron referencias a las tecnologías relacionadas con la web actual. El cliente menciono la tecnologia antigua y la deseada para la implementacion de la solucion.

- **Drupal:** mencionado en relación con la gestión de contenidos mediante un CMS.
- **Astro:** mencionado en relación con la parte frontend.
- **React:** mencionado en relación con la parte backend.

Estas referencias se recogen tal como aparecen en los apuntes y deberán verificarse con el cliente para confirmar la arquitectura actual, el papel de cada tecnología y las dificultades concretas que presenta el sistema.

## 7. Otros aspectos relevantes

### 7.1. Política de cookies

Se mencionó la política de cookies en relación con Europa. Será necesario aclarar qué requisitos se aplican actualmente y si existen diferencias respecto a otros países.

### 7.2. Organización general de la información

La variedad de contenidos, idiomas, países y programas hace necesario comprender cómo se organiza actualmente toda esta información y cómo se mantiene su coherencia entre las distintas versiones de la web.

Este aspecto deberá analizarse a partir de ejemplos concretos del funcionamiento actual, sin presuponer todavía una solución técnica.

## 8. Vocabulario del dominio

A partir de los términos recogidos durante la sesión, se propone el siguiente glosario inicial:

| Término | Significado provisional |
|---|---|
| FUNIBER | Organización cuyo contexto y actividad se están analizando. |
| Beca | Ayuda relacionada con la formación. |
| Máster | Denominación de un programa de formación superior. |
| Maestría | Denominación utilizada en determinados países para ciertos programas de formación. |
| Magíster | Término académico cuya equivalencia debe analizarse según el país. |
| CMS | Sistema de gestión de contenidos. |
| Dominio | Dirección utilizada para acceder a una web. |
| Convenio | Acuerdo entre organizaciones o instituciones. |
| Proyecto de investigación | Proyecto relacionado con la actividad investigadora. |
| Artículo científico | Publicación relacionada con la investigación. |

Este glosario es inicial. Las definiciones deberán revisarse y ampliarse según el uso concreto que haga el cliente de cada término.

## 9. Dudas y cuestiones pendientes

A partir de la información recogida, se identifican las siguientes cuestiones que convendría aclarar con el cliente:

1. ¿Qué tareas concretas resultan difíciles debido a la rigidez de la web actual?
2. ¿Qué modificaciones de contenido o estructura son las que más problemas ocasionan?
3. ¿Cómo se organizan actualmente los contenidos de los diferentes países?
4. ¿Qué relación existe entre los dominios de cada país y la web principal?
5. ¿Qué diferencias hay entre los programas académicos de cada territorio?
6. ¿Cómo se gestionan los idiomas y las traducciones?
7. ¿Qué información se almacena para cada programa, beca, universidad, convenio o proyecto?
8. ¿Qué tecnologías se utilizan actualmente y qué problemas concretos presenta su utilización?
9. ¿Qué requisitos legales específicos deben tenerse en cuenta en los distintos países?
10. ¿Cómo se gestionan los eventos, los artículos científicos y los proyectos de investigación?


Queda pendiente concretar cuáles son las principales limitaciones que experimenta el cliente, cómo afectan a su trabajo diario y qué situaciones le resultan más difíciles de gestionar.
