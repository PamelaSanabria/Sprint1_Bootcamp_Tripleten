# QA Engineer Bootcamp - TripleTen

Este repositorio contiene los resultados del primer sprint del Bootcamp de QA Engineer de **TripleTen**. Durante este sprint, el objetivo principal fue realizar pruebas de humo y de regresión en la aplicación web **Urban.Routes**, documentar los errores encontrados y priorizarlos según su severidad.

---

## Objetivos del Sprint

1. **Realizar pruebas de humo**: Asegurar que las funcionalidades críticas de la aplicación funcionan correctamente.
2. **Ejecutar pruebas de regresión**: Verificar que los cambios recientes en el sistema no introdujeron nuevos errores en las funcionalidades existentes.
3. **Documentar errores**: Identificar, detallar y priorizar los errores encontrados.
4. **Presentar un informe consolidado**: Organizar los resultados en un formato claro y accesible para compartirlos con el equipo de desarrollo.

---

## Logros del Sprint

- Se ejecutaron **pruebas de humo** exitosas que validaron las funcionalidades críticas de la aplicación.
- Durante las **pruebas de regresión**, se identificaron **10 errores** en total, los cuales fueron documentados detalladamente.
- Se clasificaron los errores por severidad: **3 errores críticos**, **2 graves**, **3 menores** y **2 triviales**.
- Se entregó un informe en formato Excel que incluye:
  - Descripción de los errores.
  - Pasos para reproducirlos.
  - Resultados esperados y reales.
  - Prioridad de corrección basada en el impacto.
  
Puedes consultar el informe completo aquí: [1.er sprint.xlsx](https://docs.google.com/spreadsheets/d/1nbUC0InzICyM3nHKtBu5oAH9wOU6VV1h/edit?usp=sharing).

---

## Errores Identificados

| ID del Error | Título                                                                                   | Severidad    |
|--------------|-------------------------------------------------------------------------------------------|--------------|
| CAS-2,1      | El mapa no coincide con el diseño; el nivel de zoom no es adecuado para ver la ciudad.    | Menor        |
| CAS-3,1      | El encabezado "Hollywood" permite interacción cuando no debería.                          | Grave        |
| CAS-4        | El campo "Desde" muestra un placeholder en lugar de estar vacío al seleccionarlo.         | Trivial      |
| CAS-5,2      | La lista de estaciones de metro no se despliega al ingresar "Subway" en el campo "Hasta". | Crítico      |
| CAS-6,2      | El mapa no enfoca correctamente al ingresar "East 2nd Street, 601" en el campo "Desde".   | Crítico      |
| CAS-7,2      | El mapa no enfoca correctamente al ingresar "1300 1st St" en el campo "Hasta".            | Crítico      |
| CAS-11,2B    | La opción "Etiquetas" no se despliega al acercar el cursor al botón "Satélite".           | Menor        |
| CAS-14,1     | El "Dodger Stadium" no se muestra ampliado en el mapa como debería.                       | Menor        |
| CAS-15       | Al hacer clic en el logotipo de Urban.Routes, no se muestra información alguna.           | Trivial      |

---

## Acerca del Bootcamp de QA Engineer de TripleTen

El Bootcamp de QA Engineer de TripleTen es un programa intensivo de 5 meses diseñado para capacitar a los participantes en las mejores prácticas de aseguramiento de calidad en software, abarcando desde pruebas manuales hasta la automatización de pruebas. Más información sobre el curso en [TripleTen](https://tripleten.com/qa-engineer/).

### Estructura del curso

- **Fundamentos de las pruebas**: Introducción a los conceptos básicos y funciones de un QA Engineer.
- **Diseño de pruebas**: Análisis de requisitos y técnicas de diseño de pruebas.
- **Pruebas de aplicaciones web**: Evaluación de la estructura y funcionalidad de aplicaciones web.
- **Pruebas de API**: Uso de herramientas como Postman para probar interfaces de programación.
- **Pruebas de aplicaciones móviles**: Evaluación de aplicaciones en dispositivos móviles y emuladores.
- **Fundamentos de bases de datos**: Manejo de bases de datos y consultas SQL.
- **Introducción a la automatización de pruebas**: Uso de lenguajes de programación y herramientas para automatizar pruebas.

---

## Contacto

Para consultas o más información, puedes contactarme a través de mi perfil de GitHub.

---

*Nota: Este repositorio es parte de mi portafolio de proyectos desarrollados durante el Bootcamp de QA Engineer de TripleTen.*
