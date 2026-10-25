# RutaSV — Aseguramiento de la Calidad del Software

##  Descripción del proyecto

**RutaSV** es una propuesta de plataforma web y móvil orientada a optimizar la logística de entregas de pequeños emprendimientos salvadoreños que comercializan sus productos mediante redes sociales.

Este proyecto académico, desarrollado en el marco de la asignatura de **Aseguramiento de la Calidad del Software (SQA)** de la Universidad Nacional de El Salvador, tiene como propósito establecer y simular un marco de aseguramiento de la calidad para evaluar las características, los riesgos y la experiencia de uso de la plataforma.

##  Objetivo

Definir un enfoque sistemático para evaluar la calidad del producto mediante criterios de calidad, métricas, estándares, gestión de configuración y escenarios de prueba, tomando como referencia el modelo ISO/IEC 25010.

##  Alcance del proyecto

El trabajo contempla:

- **Modelo de calidad:** análisis de características de calidad basadas en ISO/IEC 25010.
- **Plan SQA:** planificación de actividades para asegurar y evaluar la calidad.
- **Ciclo PHVA:** propuesta de mejora continua mediante Planificar, Hacer, Verificar y Actuar.
- **Estándares de codificación:** convenciones de nombres, comentarios y buenas prácticas.
- **Gestión de configuración (SCM):** propuesta de control de versiones, cambios e incidencias.
- **Pruebas de software:** diseño de casos de prueba funcionales, de caja negra y escenarios límite.
- **Registro de incidencias:** documentación de defectos hipotéticos, su severidad y las posibles acciones correctivas.
- **Usabilidad y experiencia de usuario (UX):** evaluación mediante escenarios simulados, principios heurísticos de Jakob Nielsen y la escala SUS.
- **Prototipos de interfaz:** representación conceptual de las pantallas para emprendedores, repartidores y clientes.

##  Enfoque de pruebas

Se plantearon escenarios para evaluar el comportamiento esperado de RutaSV, incluyendo:

- Gestión de rutas sin asignaciones.
- Validación de campos obligatorios, como el teléfono del cliente.
- Restricción de rutas a un máximo de 20 direcciones.
- Validación de comprobantes de entrega y sincronización en modo sin conexión.
- Evaluación de tareas habituales del repartidor.

Los resultados simulados permiten identificar riesgos y proponer mejoras antes de una eventual implementación.

##  Herramientas y recursos considerados

Las herramientas contempladas en la propuesta incluyen:

- **Git y GitHub:** control de versiones y seguimiento de cambios.
- **JUnit y Jest:** frameworks considerados para pruebas automatizadas, según la tecnología de cada componente.
- **Postman:** pruebas de servicios API.
- **SonarQube:** análisis estático de calidad del código.
- **Figma:** diseño y exploración de prototipos de interfaz.

> Nota: estas herramientas forman parte de la propuesta de trabajo; su inclusión no implica que todas se hayan ejecutado sobre una aplicación implementada.

##  Funcionalidades conceptuales de RutaSV

- Gestión y seguimiento de pedidos.
- Organización de rutas de entrega.
- Registro de comprobantes mediante fotografía.
- Consulta de mapas y datos principales del cliente sin conexión, cuando las rutas y los datos necesarios se hayan descargado previamente.
- Sincronización de entregas pendientes al recuperar la conexión.
- Interfaces diferenciadas para emprendedores, repartidores y clientes.

## Resultados esperados

El proyecto busca demostrar cómo la planificación de la calidad, el diseño de pruebas, la documentación de incidencias y la evaluación de usabilidad contribuyen a identificar riesgos y proponer mejoras para un producto de software.

## 🎓 Contexto académico

- **Proyecto:** RutaSV
- **Asignatura:** Aseguramiento de la Calidad del Software (SQA)
- **Institución:** Universidad Nacional de El Salvador
- **Modalidad:** proyecto académico grupal

## Nota sobre el alcance

RutaSV se presenta como un proyecto académico de aseguramiento de la calidad. Los casos de prueba, defectos y resultados descritos como simulados o hipotéticos no deben interpretarse como evidencia de que una aplicación productiva fue implementada y probada en su totalidad.
puedes visualizar aca : https://www.figma.com/make/sUZcNKMFr9jc8TVxXzx3bZ/RutaSV-Logistics-App-Design?t=91VaIoRQCDNEIvc2-1

*RutaSV — La calidad se planifica, se evalúa y se mejora continuamente.*
