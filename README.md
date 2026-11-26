<h1 align="center">26-27-IdSw1-SDR · Reorganización web de FUNIBER</h1>

<p align="center">
  <b>Unificación de la web por países y gestor web de contenidos</b><br>
  <i>Universidad Europea del Atlántico · Ingeniería del Software I · Curso 2026–2027 · Grupo 3</i>
</p>

<br>

<div align="center">

| Clienta | Organización | Rama de trabajo |
| :---: | :---: | :---: |
| Lucía Terán | [FUNIBER](https://www.funiber.org) | `grupo-3` |

</div>

---

## Descripción del proyecto

**FUNIBER** trabaja en becas, programas de máster y formación universitaria en varios países. Su web actual es demasiado rígida para hacer cambios, y cada país tiene su propio dominio (funiber.es, funiber.pt…), que compite en posicionamiento con el principal.

El proyecto recoge los requisitos para:

> **Unificar la web** bajo funiber.org, con un directorio por país.
>
> **Disponer de un gestor web** con el que el personal técnico edite componentes y contenidos.

El trabajo se organiza en dos bloques: **FUNIBER**, que describe cómo funciona hoy la organización, y **GESTOR-WEB**, que describe la solución propuesta.

<br>

---

## [Modelo del dominio](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/grupo-3/documentos/modeloDeDominio)

Conceptos del negocio expresados con el vocabulario de la clienta.

| Contenido | Descripción |
| :--- | :--- |
| **[Modelo del estado actual](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/grupo-3/documentos/modeloDeDominio/propuestaActual)** | Bloque FUNIBER: la organización tal como funciona hoy, con sus iteraciones |
| **[Modelo de la solución](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/grupo-3/documentos/modeloDeDominio/propuestaSoluci%C3%B3n)** | Bloque GESTOR-WEB: el gestor que se propone |
| **[Modelo por bloques](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/feature/9-transcribir-a-plantuml-y-encontrar-atributos/documentos/modeloDeDominio/propuestaSolucionDividida)** | Los dos bloques unidos en un solo diagrama, con sus atributos |
| **Glosario** | Términos del dominio y su significado |

<br>

---

## [Diagramas de estados](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/feature/diagramas-de-estados/documentos/modeloDeDominio/diagramaDeEstados)

Ciclo de vida de las entidades principales del dominio.

| Entidad | Bloque |
| :--- | :--- |
| **[Publicación](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/feature/diagramas-de-estados/documentos/modeloDeDominio/diagramaDeEstados/diagramaEstadosPublicacion.svg)** | FUNIBER |
| **[Obra cultural](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/feature/diagramas-de-estados/documentos/modeloDeDominio/diagramaDeEstados/diagramaEstadosObra-cultural.svg)** | FUNIBER |
| **[Versión](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/feature/diagramas-de-estados/documentos/modeloDeDominio/diagramaDeEstados/diagramaEstadosVersion.svg)** | GESTOR-WEB |

<br>

---

## [Diagramas de flujo](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/feature/diagrama-flujo-de-adaptaci%C3%B3n-de-oferta-acad%C3%A9mica/documentos/modeloDeDominio/diagramaDeFlujo)

Procesos del gestor web descritos paso a paso.

| Proceso | Bloque |
| :--- | :--- |
| **[Publicación de contenido](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/feature/diagrama-flujo-publicac%C3%ADon-contenido/documentos/modeloDeDominio/diagramaDeEstados/publicacionContenido.svg)** | GESTOR-WEB |
| **[Adaptación de la oferta académica por país](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/feature/diagrama-flujo-de-adaptaci%C3%B3n-de-oferta-acad%C3%A9mica/documentos/modeloDeDominio/diagramaDeFlujo/adaptaci%C3%B3nOfertaAcad%C3%A9micaPorPa%C3%ADs.svg)** | GESTOR-WEB |

<br>

---

## [Actores y casos de uso](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/feature/diagramas-de-contexto/documentos/modeloDeDominio/diagramasDeContexto)

Quién usa el sistema y qué objetivos tiene cada actor.

| Contenido | Descripción |
| :--- | :--- |
| **[Diagramas de contexto](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/feature/diagramas-de-contexto/documentos/modeloDeDominio/diagramasDeContexto)** | Casos de uso disponibles para cada actor: Administrador, Editor y Usuario |
| **Actores y casos de uso** | Identificación de los roles y de sus objetivos |
| **Priorización** | Orden en que se abordan los casos de uso y criterios empleados |
| **Casos de uso detallados** | Flujo de cada caso de uso |
| **Prototipos** | Bocetos de interfaz de cada caso de uso |

<br>

---

## [Sesiones con la clienta](https://github.com/vanepakk/26-27-IdSw1-SDR/tree/grupo-3/documentos/sesiones)

Minutas de las reuniones de requisitado: temas tratados, vocabulario del dominio y dudas pendientes.

| Sesión | Fecha | Objetivo |
| :---: | :---: | :--- |
| **[Sesión 1](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/grupo-3/documentos/sesiones/sesion01.md)** | 26/10/2026 | Primer acercamiento al problema y al contexto de FUNIBER |
| **[Sesión 2](https://github.com/vanepakk/26-27-IdSw1-SDR/blob/grupo-3/documentos/sesiones/sesion02.md)** | 25/11/2026 | Aclaración de dudas y propuesta de gestor web |

<br>

---

## Estructura del repositorio

```text
26-27-IdSw1-SDR/
├── README.md                       # Índice del proyecto
├── AI-uso.md                       # Declaración de uso de IA
├── images/                         # Imágenes de apoyo
└── documentos/
    ├── sesiones/                   # Minutas de las sesiones con la clienta
    └── modeloDeDominio/            # Fuentes PlantUML (.puml) y exportaciones (.svg)
        ├── propuestaActual/        # Modelo del estado actual (FUNIBER)
        ├── propuestaSolución/      # Modelo de la solución (GESTOR-WEB)
        ├── diagramaDeEstados/      # Diagramas de estados
        ├── diagramaDeFlujo/        # Diagramas de flujo
        └── diagramasDeContexto/    # Diagramas de contexto por actor
```