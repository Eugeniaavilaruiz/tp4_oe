# Sistema de Ventas y Reservas Online – Neige et Soleil

Trabajo Práctico Integrador (TPI) – Organización Empresarial
Tecnicatura Universitaria en Programación a Distancia – Universidad Tecnológica Nacional

## Descripción del sistema

Sistema web de ventas y reservas online para el área de Comercialización de Neige et Soleil,
empresa de estadías educativas y colonias de vacaciones ubicada en Val-Cenis, Francia.
El sistema permite a familias, escuelas y colonias consultar la disponibilidad de alojamientos,
realizar reservas y pagarlas online, y organiza la información de las reservas para el resto
de las áreas de la organización.

## Integrantes

- Eugenia Avila Ruiz

## Proceso de negocio (BPMN)

![Diagrama BPMN del proceso de reserva online](bpmn_proceso_reserva.png)

El diagrama modela el proceso de reserva online que automatiza el sistema. Se organiza en tres pools: Cliente y Pasarela de pago, como participantes externos, y Neige et Soleil, con tres lanes: Ventas y Reservas online, Sistema de ventas y reservas (comportamiento automatizado) y Finanzas y Control.

El flujo estándar va desde la solicitud de reserva hasta su confirmación. Las excepciones se resuelven mediante compuertas: falta de disponibilidad, pago rechazado y vencimiento del plazo de pago, este último con una compuerta basada en eventos y un temporizador de 30 minutos.

Los estados de la reserva (Pendiente, Confirmada y Cancelada) coinciden con los valores del campo `estado` de la entidad Reserva del diccionario de datos (Entrega N.º 3).
