# Revisión de seguridad — 2026-10-24

Repositorio: `JulianKizeno/lab-authentication-with-passport`. Rama: `security/review-2026-10-24`.

## Correcciones

- Update vulnerable dependencies: mongoose ^6.13.12
- Remove committed environment values and add a value-free template; rotate any previously exposed credentials/signing secrets (history retained)

## Auditoría npm después de los cambios

| Proyecto | Críticas | Altas | Moderadas | Bajas | Total |
|---|---:|---:|---:|---:|---:|
| `.` | 0 | 0 | 0 | 0 | 0 |

## Verificación

- Inicialización de servidor (`.`) con APIs reales de las dependencias y conexión de base de datos aislada: correcta.

## Límites y configuración

- La auditoría cubre el árbol npm resuelto, no demuestra ausencia de vulnerabilidades de lógica, infraestructura o servicios externos. No se ha desplegado ni fusionado este cambio.
- Los archivos .env se sustituyen por ejemplos sin valores. Rotar cualquier credencial o secreto publicado previamente; eliminarlo de esta rama no lo borra del historial.
