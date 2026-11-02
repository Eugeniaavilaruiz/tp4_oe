# Sistema de Ventas y Reservas Online – Neige et Soleil

Trabajo Práctico Integrador (TPI) – Organización Empresarial
Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional

## Descripción del sistema

Sistema web de ventas y reservas online para el área de Comercialización de Neige et Soleil,
empresa de estadías educativas y colonias de vacaciones ubicada en Val-Cenis, Francia.
El sistema permite a familias, escuelas y colonias consultar la disponibilidad de alojamientos,
realizar reservas y pagarlas online, y organiza la información de las reservas para el resto
de las áreas de la organización.

## Gestión del proyecto

- Tablero ágil (GitHub Projects): [Backlog TPI – Neige et Soleil](LINK_DEL_TABLERO)
- El backlog contiene las tres historias de usuario del sistema (HU1, HU2 y HU3), cargadas como issues del repositorio, con seguimiento de sus estados: Por hacer, En progreso y Listo.
- Los cambios de la documentación se integraron mediante ramas secundarias y Pull Requests. La revisión de los Pull Requests fue realizada por la propia autora por tratarse de un trabajo individual; los comentarios y correcciones quedan documentados en cada PR.

## Mecanismos de control

Para la auditoría técnica del sistema se definen los siguientes indicadores, con su estándar de desempeño y su frecuencia de medición. Varios retoman las metas cuantitativas de la Entrega N.º 2.

| Indicador | Qué mide | Estándar de desempeño | Frecuencia |
|---|---|---|---|
| Tiempo de respuesta | Carga del catálogo y confirmación de una reserva | 3 segundos o menos en el 95 % de las solicitudes (meta M2) | Semanal |
| Disponibilidad | Porcentaje del tiempo en que el sistema está en línea | 99 % o más | Mensual |
| Capacidad | Usuarios simultáneos sin pérdida de rendimiento | 100 usuarios simultáneos (meta M3) | Antes de cada temporada alta |
| Pagos rechazados por fallas técnicas | Pagos que fallan por errores del sistema o de la pasarela, sobre el total | 2 % o menos | Semanal |
| Reservas canceladas por vencimiento | Reservas en estado Pendiente que pasan a Cancelada por vencer el plazo de pago | 15 % o menos | Mensual |
| Calidad del software | Casos de prueba aprobados y errores críticos sin resolver | 95 % o más de casos aprobados y 0 errores críticos (meta M5) | Antes de cada nueva versión |

Los indicadores de pagos rechazados y de reservas canceladas por vencimiento miden directamente las excepciones modeladas en el BPMN.

## Integrantes

- Eugenia Avila Ruiz
