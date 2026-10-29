# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda
Buscar recetas

Como [rol], quiero [capacidad amplia], para [beneficio].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división
[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Buscar recetas mediante una palabra o frase

Como usuario quiero poder buscar recetas mediante una palabra o una frase para poder ver el tipo de recetas que deseo

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que intenta buscar una receta mediante una palabra, cuando ninguna de las recetas disponibles tengan el nombre introducido, entonces el sistema no muestra ninguna receta y informa al usuario que no hay recetas disponibles con el nombre introducido.
- **CA-02.** Dado un usuario que intenta buscar una receta mediante una frase, cuando no hay recetas que su nombre o sus ingredientes contengan la frase completa, entonces el sistema muestra al usuario las recetas que su nombre o sus ingredientes contengan al menos una palabra de la frase introducida.
- **CA-03.** Dado un usuario que intenta buscar recetas mediante una palabra, cuando existen recetas que contengan la palabra introducida, entonces el sistema muestra al ususario las recetas encontradas ordenadas por relevancia.

## US-02

**Título:** Buscar recetas por ingredientes incluidos

Como usuario, quiero poder buscar recetas por ingredientes incluidos, para poder ver las recetas que contengan solo los ingredientes que puedo tomar.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que busca recetas mediante ingredientes incluidos, cuando haya recetas con los ingredientes introducidos por el usuario, entonces muestra las recetas encontradas ordenadas por relevancia.
- **CA-02.** Dado un usuario que intenta buscar recetas mediante ingredientes incluidos, cuando no haya ningúna receta que contenga al menos uno de los ingredientes introducidos por el usuario, entonces el sistema no muestra recetas, y informa al usuario de que no hay recetas que tienen los ingredientes introducidos.
- **CA-03.** Dado un usuario que busca recetas por ingredientes incluidos, cuando hay solo recetas que contengan algunos de los ingrediendes introducidos, entonces el sistema muestra las recetas encontradas ordenadas por relevancia.

## US-03

**Título:** Buscar recetas por ingredientes excluidos

Como usuario, quiero buscar recetas mediante ingredientes excluidos, para ver las recetas que no contengan ingredientes que no puedo tomar.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado un usuario que busca recetas por ingredientes excluidos, cuando todas las recetas que están disponibles contienen los ingredientes que el usuario haya intruducido, entonces el sistema no muestra ninguna receta y avisa al usuario de que no existen recetan con los filtros que ha introducido.
- **CA-02.** Dado un usuario que intenta buscar recetas po ingredientes excluidos, cuando haya recetas que no contengan dichos ingredientes introducidos por el usuario, entonces el sistema muestra las recetas encontradas ordenadas por relevancia.
- **CA-03.** Dado un usuario que intenta buscar recatas por ingredientes excluidos, cuando haya recetas que contengan el menos uno de los ingredientes elegidos por el usuario, entonces el sistema no muestra dichas recetas y avisa el usuario de que no existen recetas que no contengan ninguno de los ingredientes que desea excluir.

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. |  SÍ  |  SÍ  | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | SÍ |  SÍ  | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | SÍ |  SÍ  | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? |  SÍ  |  SÍ  | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? |  SÍ  |  SÍ  | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? |  SÍ  | SÍ  | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
