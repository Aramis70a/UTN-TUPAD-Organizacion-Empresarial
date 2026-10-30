# Evidencias de versionado y tablero ágil

## Repositorio público

<https://github.com/Aramis70a/UTN-TUPAD-Organizacion-Empresarial>

## Ramas

| Rama | Contenido |
| --- | --- |
| `main` | Versión estable y entregable. |
| `develop` | Integración de los trabajos. |
| `feature/bpmn` | Documentación y diagrama BPMN. |
| `feature/backlog` | Backlog, control y declaración de IA. |
| `feature/evidencias` | Evidencias de versionado y tablero (este PR). |

## Pull Requests fusionados

| PR | Origen | Contenido |
| --- | --- | --- |
| #4 | `feature/evidencias` → `main` | Evidencias de versionado y tablero ágil (PR fusionado con revisión de pares). |

La documentación del BPMN y el backlog se integró desde sus ramas (`feature/bpmn` y `feature/backlog`) mediante commits de merge en `develop`, y luego `develop` se integró en `main`.

## Tablero ágil (GitHub Projects)

<https://github.com/users/Aramis70a/projects/1>

| Historia de Usuario | Estado |
| --- | --- |
| HU-01 — Solicitud de propuesta | Listo |
| HU-02 — Registro de horas y avance | En Progreso |
| HU-03 — Facturación y cobranzas | Por Hacer |

## Trazabilidad

Cada Historia de Usuario está asociada a un *issue* del repositorio y a una tarjeta del tablero, de modo que el estado del backlog puede auditarse en todo momento desde GitHub.
