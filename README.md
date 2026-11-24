# Sesiones de requisitado

Este es el repositorio de las sesiones de requisitado de la asignatura de Ingeniería del Software I de UNEATLANTICO.

Se desarrolla, en un caso real, la disciplina de requisitado, que es la puerta de entrada al desarrollo de una solución basada en software. 

<div align=center>

| |Coordinador|Cliente|Estadísticas|
|-|-|-|:-:|
|1|@Angelo2272| |[👁️](https://github.com/Angelo2272/26-27-IdSw1-SDR) / 📒
|2|@Raultascon| |[👁️](https://github.com/Raultascon/26-27-IdSw1-SDR) / 📒
|3|@vanepakk| |[👁️](https://github.com/vanepakk/26-27-IdSw1-SDR) / 📒
|4|@Alejandracuesta| |[👁️](https://github.com/Alejandracuesta/26-27-IdSw1-SDR) / 📒
|5|@Silviamontes43| |[👁️](https://github.com/Silviamontes43/26-27-IdSw1-SDR) / 📒
|6|@Paula-Oreja| |[👁️](https://github.com/Paula-Oreja/26-27-IdSw1-SDR) / 📒

</div>

> Se ha demostrado, empírica y académicamente, que un porcentaje no menor de proyectos de software que fracasan lo hacen porque está mal llevada esta fase.

<div align=center>

||
|-|
![](https://raw.githubusercontent.com/mmasias/23-24-IdSw1-SDR/main/imagenes/modelosUML/trabajoRepos.svg)

</div>

## Algunas reglas

- Reuniones oficiales (en horas de clase)
  - A estas debe asistir el 100% de los integrantes de los grupos.
  - Si a las reuniones asiste menos del 80% del grupo, la reunión se cancela y el grupo se da por cerrado. La evaluación se realiza de la forma tradicional (examen parcial, examen final).
- Reuniones extra: de acuerdo a lo pautado con el cliente.
- Se recomienda utilizar el repo del coordinador del grupo y las herramientas de GitHub para gestionar las reuniones y comunicaciones con el cliente, haciendo racional uso de la trazabilidad.
- Las imágenes, en la medida de lo posible en formato plantUML. 
  - Todas las fuentes en la carpeta modelosUML y las imágenes exportadas, en formato svg.

## Propuesta de solución: Gestor Web

El modelo final y sus iteraciones están disponibles en `modelosUML/`:

| Versión | Fuente PlantUML | Diagrama SVG |
|---|---|---|
| Iteración 1 | [iteracion1GestorWeb.puml](modelosUML/iteracion1GestorWeb.puml) | [iteracion1GestorWeb.svg](modelosUML/iteracion1GestorWeb.svg) |
| Iteración 2 | [iteracion2GestorWeb.puml](modelosUML/iteracion2GestorWeb.puml) | [iteracion2GestorWeb.svg](modelosUML/iteracion2GestorWeb.svg) |
| Final | [modeloDominioSolucionGestorWeb.puml](modelosUML/modeloDominioSolucionGestorWeb.puml) | [modeloDominioSolucionGestorWeb.svg](modelosUML/modeloDominioSolucionGestorWeb.svg) |

### Conclusiones para la revisión cruzada

Las iteraciones refinan la propuesta desde un Gestor Web que centraliza las seis responsabilidades hasta un modelo con entidades y relaciones explícitas. El modelo final relaciona cada responsabilidad con los elementos del dominio que modifica: el sitio y sus dominios; los directorios y países; los apartados; el contenido común; y las denominaciones adaptadas por país.

La centralización de dominios y contenido permite mantener una estructura común, mientras que los directorios y las denominaciones permiten organizar y presentar la información según el país. El repositorio no incluye el modelo del dominio final previo; por ello, esta propuesta toma como base los conceptos y responsabilidades descritos en el issue y deja la validación de correspondencia con aquel modelo para la revisión cruzada.
