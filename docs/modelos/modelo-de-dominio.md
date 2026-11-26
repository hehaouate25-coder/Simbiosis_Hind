# Modelo de dominio de Proyecto Simbiosis

| Versión | Fecha | Estado |
| --- | --- | --- |
| 1.1 | 24/11/2026 | Plantilla |

Al crear el modelo a partir de esta plantilla, actualiza esta tabla con la versión, la fecha y el estado del documento de trabajo.

## 1 Propósito y alcance

Indica las áreas ya representadas, las partes todavía pendientes y los límites del análisis. Conserva este documento y amplíalo conforme avance el modelo.

## 2 Fuentes y convenciones

Consulta el [acta de información del dominio](../captura/acta-acuerdos-informacion-dominio.md), el [Documento de Visión](../vision/vision_y_alcance.md), la [SRS y su glosario](../requisitos/srs.md) y el [catálogo](../requisitos/catalogo-requisitos.md). Distingue los acuerdos confirmados de las propuestas provisionales y de los aspectos aplazados.

Representa clases conceptuales, atributos y relaciones. Cada clase pertenece a un paquete de origen y puede aparecer en varias vistas del mismo modelo. Los nombres de archivo no llevan versiones; Git conserva los estados registrados.

## 3 Vistas del modelo de dominio

Exporta cada vista trabajada a PNG en `docs/modelos/imagenes/Análisis.png` y añade aquí su imagen mediante un enlace relativo. Mientras una imagen no exista, conserva únicamente el texto de pendiente; no añadas enlaces rotos.

### 3.1 Gestión de usuarios

Pendiente. Imagen prevista: `clases-dominio-gestion-usuarios.png`. Fuente principal: acta §2 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Gestión-de-Usuarios" src="https://github.com/user-attachments/assets/b4ca10a4-0309-4c0b-88f2-f33fe5c80a98" />


### 3.2 Gestión de recetas

Pendiente. Imagen prevista: `clases-dominio-gestion-recetas.png`. Fuente principal: acta §3 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Gestión-de-Recetas" src="https://github.com/user-attachments/assets/774c0527-aaf2-4297-9753-11c95c81b71c" />

### 3.3 Foro

Pendiente. Imagen prevista: `clases-dominio-foro.png`. Fuente principal: acta §4 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Foro" src="https://github.com/user-attachments/assets/63b8f269-8dfc-40f4-bd95-5251ea11c31c" />

### 3.4 Gestión de datos de salud

Pendiente. Imagen prevista: `clases-dominio-gestion-datos-salud.png`. Fuente principal: acta §5 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Gestión-de-Datos-de-Salud" src="https://github.com/user-attachments/assets/cfddafde-a30d-4b95-a2de-8ca1391bfdbc" />

### 3.5 Gestión de publicaciones de salud

Pendiente. Imagen prevista: `clases-dominio-gestion-publicaciones-salud.png`. Fuente principal: acta §6 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Gestión-de-Publicaciones-de-Salud" src="https://github.com/user-attachments/assets/a3f43984-0452-46e3-a199-01d0f099a283" />

### 3.6 Moderación de contenidos

Pendiente. Imagen prevista: `clases-dominio-moderacion-contenidos.png`. Fuente principal: acta §7 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Moderación-de-Contenidos" src="https://github.com/user-attachments/assets/1e4eb949-3a87-497a-b37d-1b68e96df96f" />

### 3.7 Guía interactiva

Pendiente. Imagen prevista: `clases-dominio-guia-interactiva.png`. Fuente principal: acta §8 y acuerdos del apartado 9.
<img width="1920" height="1020" alt="Módulo-Guía-Interactiva" src="https://github.com/user-attachments/assets/6e50a5b2-907d-45af-a603-347507b39d9d" />

### 3.8 Organización en paquetes

Pendiente. Imagen prevista: `paquetes-dominio.png`. Paquete raíz: `Dominio`. Paquetes funcionales: `01 Usuarios`, `02 Recetas`, `03 Foro`, `04 Datos de Salud`, `05 Publicaciones de Salud`, `06 Moderación de Contenidos`, `07 Guía Interactiva`.

Incluye las clases que ayuden a explicar la organización. Por cada dependencia, indica qué clase referenciada la justifica y cuál es su paquete de origen. Conserva el carácter parcial del trabajo si todavía faltan áreas.

## 4 Justificación de las decisiones

Anota solo las decisiones que necesitan explicación y su respaldo en el acta o los requisitos. No transcribas el catálogo ni describas en texto cada elemento ya visible en las figuras.

## 5 Fuentes de las vistas

Relaciona cada vista trabajada con el apartado del acta y las referencias que hayas utilizado. Basta una referencia breve por vista y las precisiones necesarias.

## 6 Cuestiones abiertas

Registra preguntas concretas y aspectos aplazados. Si utilizas una propuesta provisional del acta, conserva esa condición. No inventes reglas para completar el diagrama.

## 7 Revisión y evolución

Resume el estado del modelo y las decisiones revisadas. Guarda el documento y sus imágenes en el mismo commit para poder recuperar una versión completa.
