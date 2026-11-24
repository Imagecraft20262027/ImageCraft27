# ImageCraft – Gestión Ágil de un Proyecto Software

## Hito 1: Configuración del equipo y propuesta de proyecto

**Proyecto:** ImageCraft  
**Tipo:** API REST para el procesamiento de imágenes  
**Tecnología principal:** Python + FastAPI  
**Metodología de trabajo:** Scrum  
**Número de integrantes:** 8 personas

---

## 1. Descripción del proyecto

**ImageCraft** es un proyecto software que consiste en desarrollar una API REST utilizando Python y el framework FastAPI, cuyo objetivo es permitir el procesamiento y la edición básica de imágenes mediante diferentes endpoints.

La API ofrecerá funcionalidades para modificar imágenes de forma sencilla, permitiendo a los usuarios realizar operaciones como eliminar fondos, añadir marcas de agua, cambiar dimensiones y aplicar filtros.

El proyecto busca proporcionar una solución sencilla, modular y eficiente que permita realizar operaciones sobre imágenes mediante peticiones HTTP, facilitando su integración con otras aplicaciones y servicios.

### 1.1. Objetivos principales

- Desarrollar una API REST utilizando FastAPI.
- Implementar diferentes operaciones de procesamiento de imágenes.
- Permitir la recepción y devolución de imágenes mediante peticiones HTTP.
- Proporcionar documentación interactiva de los endpoints mediante Swagger UI.
- Aplicar buenas prácticas de desarrollo, organización y trabajo colaborativo.
- Gestionar el desarrollo del proyecto utilizando la metodología ágil Scrum.

### 1.2. Funcionalidades principales

La API contará inicialmente con los siguientes endpoints:

| Funcionalidad | Descripción |
|---|---|
| Eliminar fondo | Permitir eliminar o hacer transparente el fondo de una imagen. |
| Añadir marca de agua | Insertar texto o una imagen como marca de agua. |
| Cambiar tamaño | Modificar las dimensiones de una imagen. |
| Aplicar filtros | Aplicar filtros como blanco y negro, sepia, desenfoque o nitidez. |
| Recortar imagen | Recortar una imagen indicando las dimensiones o coordenadas deseadas. |
| Convertir formato | Transformar imágenes entre formatos como PNG, JPEG y WEBP. |

### 1.3. Tecnologías previstas

- **Python:** lenguaje principal de programación.
- **FastAPI:** framework para desarrollar la API REST.
- **Pillow (PIL):** biblioteca para el procesamiento y manipulación de imágenes.
- **OpenCV:** biblioteca opcional para operaciones avanzadas de procesamiento de imágenes.
- **Uvicorn:** servidor ASGI para ejecutar la aplicación.
- **Swagger UI:** documentación y pruebas interactivas de los endpoints.
- **Git y GitHub:** control de versiones y colaboración.

---

## 2. Configuración del equipo Scrum

El equipo estará formado por ocho integrantes, distribuidos entre los diferentes roles de Scrum.

### 2.1. Integrantes y responsabilidades

| Integrante | Rol | Correo electrónico |
|---|---|---|
| Alejandro Muñoz Pérez | Scrum Master | amp1078@alu.ubu.es |
| Elías García Cortés | Product Owner | egc1022@alu.ubu.es |
| Alejandro José Álvarez López | Desarrollador | aal1032@alu.ubu.es |
| Fabián Ubilla | Desarrollador | fuv1001@alu.ubu.es |
| Roberto Iturralde Zarzo | Desarrollador | riz1001@alu.ubu.es |
| Andrés Catalán Arenas | Desarrollador | aca1053@alu.ubu.es |
| Mariya Georgieva Minova | Desarrolladora | mgm0233@alu.ubu.es |
| Aya Dahmani | Desarrolladora | adx1045@alu.ubu.es |

### 2.2. Responsabilidades de los roles

**Scrum Master – Alejandro Muñoz Pérez**

- Facilitar la aplicación de Scrum.
- Organizar y coordinar las ceremonias.
- Identificar y ayudar a resolver impedimentos.
- Favorecer la comunicación entre los integrantes.
- Supervisar que se respeten los acuerdos de trabajo.

**Product Owner – Elías García Cortés**

- Definir y comunicar los objetivos del producto.
- Gestionar y priorizar el Product Backlog.
- Definir y aclarar las historias de usuario.
- Establecer los criterios de aceptación.
- Validar que los incrementos desarrollados aporten valor.

**Desarrolladores – Resto del equipo**

- Diseñar e implementar los endpoints de la API.
- Realizar pruebas y verificar el funcionamiento.
- Revisar el código de los compañeros.
- Mantener actualizada la documentación.
- Participar en las ceremonias Scrum.
- Colaborar para alcanzar los objetivos de cada Sprint.

---

## 3. Organización y adaptación de Scrum al entorno online

El equipo utilizará Scrum como metodología ágil de desarrollo, organizando el trabajo en Sprints y realizando las ceremonias de manera online.

### 3.1. Sprint Planning

**Herramientas:** Microsoft Teams y GitHub Projects.

**Dinámica:**

Se realizará una reunión síncrona en la que el Product Owner expondrá las historias de usuario prioritarias del Product Backlog.

El equipo analizará las tareas necesarias, debatirá las estimaciones y seleccionará los elementos que se incorporarán al Sprint Backlog.

Finalmente, se establecerá un objetivo para el Sprint y se distribuirá el trabajo entre los desarrolladores.

### 3.2. Daily Scrum

**Herramientas:** Microsoft Teams y Telegram.

**Dinámica:**

Se combinarán dos modalidades de seguimiento:

- **Daily síncrona:** reunión formal mediante Microsoft Teams, con invitación al profesor (dseto@ubu.es) y grabación de la sesión.
- **Daily asíncrona:** actualización diaria mediante Telegram para facilitar el seguimiento de todos los integrantes.

Cada miembro responderá a las siguientes preguntas:

1. ¿Qué hice ayer?
2. ¿Qué voy a hacer hoy?
3. ¿Tengo algún impedimento que dificulte mi trabajo?

El objetivo es mantener una comunicación constante y detectar rápidamente posibles problemas.

### 3.3. Sprint Review

**Herramientas:** Microsoft Teams y Swagger UI.

**Dinámica:**

Al finalizar cada Sprint se realizará una demostración del incremento desarrollado.

Se compartirá la aplicación y se ejecutarán los endpoints desde Swagger UI, disponible en la ruta `/docs` de FastAPI.

Se comprobará el funcionamiento de las funcionalidades implementadas y se recogerá el feedback del Product Owner y de los participantes.

### 3.4. Sprint Retrospective

**Herramientas:** Microsoft Teams y Microsoft Whiteboard.

**Dinámica:**

El equipo analizará cómo ha funcionado el Sprint, identificando aspectos positivos y problemas que hayan afectado al desarrollo.

Se responderán tres cuestiones principales:

- ¿Qué ha funcionado bien?
- ¿Qué problemas o dificultades hemos encontrado?
- ¿Qué podemos mejorar en el siguiente Sprint?

Se establecerán acuerdos de mejora concretos para incrementar la eficiencia y la colaboración del equipo.

### 3.5. Gestión de impedimentos

**Herramientas:** Telegram y GitHub Issues.

**Dinámica:**

Cualquier integrante podrá comunicar un impedimento a través del grupo de Telegram o creando una incidencia en GitHub con la etiqueta `impediment`.

El Scrum Master será responsable de realizar el seguimiento y facilitar la resolución de los problemas para evitar que afecten al progreso del Sprint.

---

## 4. Herramientas de trabajo y colaboración

Para facilitar la organización, comunicación y desarrollo del proyecto se utilizarán las siguientes herramientas:

| Herramienta | Utilidad |
|---|---|
| Git | Control de versiones del código fuente. |
| GitHub | Repositorio central y colaboración. |
| GitHub Projects | Gestión del Product Backlog y Sprint Backlog. |
| GitHub Issues | Registro de tareas, errores e impedimentos. |
| Microsoft Teams | Reuniones y ceremonias Scrum. |
| Telegram | Comunicación rápida y seguimiento diario asíncrono. |
| Swagger UI | Documentación y pruebas de la API REST. |
| Python | Desarrollo de la aplicación. |
| FastAPI | Implementación de los endpoints. |

### 4.1. Organización del repositorio

Se propone la siguiente estructura inicial:

```text
ImageCraft/
│
├── app/
│   ├── main.py
│   ├── routers/
│   │   ├── background.py
│   │   ├── watermark.py
│   │   ├── resize.py
│   │   ├── filters.py
│   │   └── crop.py
│   │
│   ├── services/
│   │   └── image_service.py
│   │
│   └── utils/
│       └── image_utils.py
│
├── tests/
│   ├── test_background.py
│   ├── test_watermark.py
│   ├── test_resize.py
│   └── test_filters.py
│
├── requirements.txt
├── .gitignore
└── README.md
```

Esta estructura permitirá separar las rutas de la API, la lógica de procesamiento de imágenes y las pruebas.

---

## 5. Riesgos del proyecto y medidas de mitigación

Durante el desarrollo de ImageCraft pueden surgir diferentes riesgos que afecten a la planificación y al cumplimiento de los objetivos.

| Riesgo | Impacto | Medida de mitigación |
|---|---|---|
| Falta de comunicación | Alto | Realizar reuniones periódicas y mantener Telegram activo. |
| Retrasos en las tareas | Alto | Dividir las historias de usuario en tareas pequeñas y realizar seguimiento diario. |
| Conflictos al integrar código | Medio | Utilizar ramas independientes y Pull Requests. |
| Errores en el procesamiento de imágenes | Alto | Implementar pruebas unitarias y validar los formatos de entrada. |
| Desconocimiento de FastAPI o Pillow | Medio | Compartir documentación y realizar pequeñas pruebas técnicas. |
| Ausencia de algún integrante | Medio | Documentar el trabajo y evitar que las tareas críticas dependan de una sola persona. |
| Problemas de coordinación online | Medio | Establecer horarios y canales de comunicación claros. |
| Imágenes demasiado grandes | Alto | Establecer límites de tamaño y validar los archivos recibidos. |

---

## 6. Propuesta inicial del Product Backlog

El Product Backlog contendrá las funcionalidades y mejoras que se desarrollarán durante el proyecto.

| ID | Historia de usuario | Prioridad |
|---|---|---|
| HU-01 | Como usuario, quiero subir una imagen para poder procesarla. | Alta |
| HU-02 | Como usuario, quiero eliminar el fondo de una imagen. | Alta |
| HU-03 | Como usuario, quiero añadir una marca de agua a una imagen. | Media |
| HU-04 | Como usuario, quiero cambiar el tamaño de una imagen. | Alta |
| HU-05 | Como usuario, quiero aplicar filtros a una imagen. | Alta |
| HU-06 | Como usuario, quiero recortar una imagen. | Media |
| HU-07 | Como usuario, quiero convertir una imagen a otro formato. | Media |
| HU-08 | Como usuario, quiero descargar la imagen procesada. | Alta |

Las prioridades podrán modificarse según las necesidades del proyecto y la planificación de cada Sprint.

---

## 7. Criterios generales de calidad

Para considerar que una funcionalidad está terminada, deberá cumplir los siguientes criterios:

- El endpoint correspondiente debe estar implementado y funcionar correctamente.
- Debe validar los datos y archivos recibidos.
- Debe devolver respuestas HTTP adecuadas.
- Debe gestionar los posibles errores.
- Debe estar documentado en Swagger UI.
- Debe contar con pruebas cuando corresponda.
- El código debe estar integrado en la rama principal mediante revisión.
- No debe introducir errores en las funcionalidades existentes.

---

## 8. Objetivo del Hito 1

Con este primer hito se pretende establecer las bases organizativas y técnicas necesarias para desarrollar ImageCraft.

Se han definido los integrantes del equipo, sus responsabilidades dentro de Scrum, las herramientas de colaboración, la adaptación de las ceremonias al entorno online y los principales riesgos del proyecto.

Asimismo, se ha establecido una propuesta inicial de producto basada en una API REST desarrollada con Python y FastAPI, orientada al procesamiento básico de imágenes.

Esta planificación servirá como punto de partida para los siguientes hitos y para la organización de los futuros Sprints.

---

## 9. Referencias y documentación técnica

- [Documentación oficial de Python](https://docs.python.org/3/)
- [Documentación oficial de FastAPI](https://fastapi.tiangolo.com/)
- [Documentación de Pillow](https://pillow.readthedocs.io/)
- [Documentación de OpenCV](https://docs.opencv.org/)
- [Documentación de Git](https://git-scm.com/doc)
- [Documentación de GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [Guía oficial de Scrum](https://scrumguides.org/scrum-guide.html)

---

**Proyecto:** ImageCraft  
**Metodología:** Scrum  
**Tecnología:** Python + FastAPI  

