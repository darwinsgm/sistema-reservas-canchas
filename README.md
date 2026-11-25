# Sistema de gestión de reservas de canchas

Proyecto final de **Ingeniería de Software 1**. Es un sistema web para un complejo de tres canchas de fútbol: los clientes consultan la disponibilidad, reservan por sí mismos y envían el comprobante del anticipo, y el administrador confirma los pagos desde un panel.

## Enlaces

- **Prototipo navegable (Figma):** https://www.figma.com/proto/DIk61UxS75bwQ4BGkjkLap/Prototipo---Reservas-de-canchas?node-id=1-5&starting-point-node-id=1%3A5&scaling=scale-down
- **Video del recorrido por el prototipo (2:24):** [video/Recorrido_prototipo_reservas_canchas.mp4](video/Recorrido_prototipo_reservas_canchas.mp4)
- **Dossier de ingeniería:** [PDF](docs/Dossier_reservas_canchas.pdf) · [Word](docs/Dossier_reservas_canchas.docx)

## Equipo

- Carlos Felipe Castaño
- Camilo Andrés Arbeláez
- Darwins Gámez
- Juliana Lugo Marín
- Brehiman Alejandro Melchor

## Qué hace el sistema

- Muestra la disponibilidad de las 3 canchas de 7:00 a.m. a 11:00 p.m., con un color por estado (libre, pendiente de pago, reservado).
- Deja reservar al cliente por sí mismo y nunca permite dos reservas en la misma cancha y hora.
- Deja la reserva en «pendiente de pago» hasta que el administrador confirma el anticipo.
- Libera el horario solo si el anticipo no se confirma en 2 horas.
- Avisa por WhatsApp, permite cancelar y cobra un valor extra en la próxima reserva si la cancelación es tardía.

## Cómo está organizado el repositorio

| Carpeta | Contenido |
| --- | --- |
| `docs/` | Dossier de ingeniería (PDF y Word) |
| `docs/entregas/` | Entregas anteriores: requisitos (U2), casos de uso (U3), checkpoint de gestión ágil (U4) y de diseño y prototipado (U5) |
| `diagramas/` | Casos de uso, arquitectura conceptual, mapa de navegación, flujo del CU2, modelo de datos y tablero Kanban |
| `prototipo/` | Enlace al prototipo de Figma y capturas de las 16 pantallas |
| `video/` | Video del recorrido por el prototipo |

## Estado del proyecto

Etapa de análisis y diseño: requisitos, historias de usuario, casos de uso, backlog, prototipo, modelo de datos, contratos, riesgos y trazabilidad. La construcción empieza con el Sprint 1 (HU-01 a HU-04: ver disponibilidad, reservar, registrar datos y evitar la doble reserva).
