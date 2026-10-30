# Dinámica de versionado — Git & GitHub

## Estructura de ramas

| Rama | Propósito |
| --- | --- |
| `main` | Versión estable y entregable del proyecto. |
| `develop` | Integración de los trabajos en curso. |
| `feature/bpmn` | Modelado del proceso en notación BPMN. |
| `feature/backlog` | Historias de Usuario y tablero ágil. |

## Convención de mensajes de commit

Se utiliza **Conventional Commits**:

```
feat: agrega diagrama BPMN del proceso de facturación
docs: documenta historias de usuario en el backlog
fix: corrige compuerta de decisión de QA
chore: actualiza estructura de carpetas del repositorio
```

## Pull Request (PR)

1. Se crea una rama secundaria a partir de `develop`.
2. Se realizan los commits descriptivos.
3. Se abre un PR hacia `develop` o `main`.
4. Se completa la lista de verificación de revisión de pares:
   - ¿Cumple los criterios de aceptación?
   - ¿La notación BPMN es correcta?
   - ¿La documentación está actualizada?
5. Se resuelven los comentarios y se fusiona el PR.

## Evidencia de versionado

El repositorio contiene al menos **un PR fusionado** con revisión, el historial de commits y las ramas secundarias utilizadas durante el desarrollo.
