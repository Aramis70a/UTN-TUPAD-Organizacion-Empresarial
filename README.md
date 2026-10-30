# Sistema de Gestión de Proyectos y Facturación — NubiaSoft S.A.

**Trabajo Práctico Integrador y Progresivo (TPI) — Entrega N.° 4: Procesos, Trabajo Colaborativo y Control Integrador**

- **Asignatura:** Organización Empresarial
- **Carrera:** Tecnicatura Universitaria en Programación a Distancia (TUP AD)
- **Institución:** Universidad Tecnológica Nacional (UTN)
- **Cuerpo de docentes:** Prof. Gabriela Martínez (titular); Prof. Carolina Bruno, Prof. Mario Raúl López y Prof. Andrea Ramos (adjuntos)
- **Integrante:** Aramis Roman Rebai Schine

## Descripción del sistema

NubiaSoft Soluciones S.A. es una empresa ficticia dedicada al desarrollo de software a medida. El sistema documentado automatiza el proceso de **gestión de proyectos y facturación**: desde la solicitud de propuesta del cliente hasta la emisión de la factura y el registro del cobro, incluyendo el control de calidad del software entregado.

El proceso se modela con notación **BPMN**, organizado en un *Pool* para la organización y otro para el cliente, con *Lanes* para los roles internos (Comercial, Desarrollo, Calidad y Sistema/Administración) y compuertas lógicas para las excepciones del proceso.

## Enlaces del proyecto

- **Repositorio público:** <https://github.com/Aramis70a/UTN-TUPAD-Organizacion-Empresarial>
- **Tablero ágil (GitHub Projects):** <https://github.com/users/Aramis70a/projects/1>

## Contenido del repositorio

| Archivo | Contenido |
| --- | --- |
| `docs/bpmn.md` | Modelado del proceso con notación BPMN (pools, lanes y compuertas). |
| `docs/backlog.md` | Historias de usuario y estado en el tablero ágil. |
| `docs/control.md` | Indicadores de control y estándares de desempeño. |
| `docs/git-workflow.md` | Ramas, commits y Pull Request del proyecto. |
| `docs/evidencias.md` | Evidencias de ramas, PR y tablero ágil. |
| `docs/declaracion-ia.md` | Declaración de uso de IA y correcciones humanas. |
| `bpmn/diagrama-bpmn.svg` | Diagrama BPMN del proceso. |

## Declaración de Uso de IA

Se utilizó un asistente de IA generativa (modelo de lenguaje) como apoyo para estructurar el documento, proponer el layout del diagrama BPMN y revisar el estilo. Los prompts principales fueron:

1. «Proponé la estructura de un TPI de Organización Empresarial con BPMN, Git/GitHub y backlog ágil.» → **corrección humana:** se descartaron secciones ajenas a la consigna y se respetó el orden pedido por la cátedra.
2. «¿Cómo modelar en BPMN el proceso de gestión de proyectos y facturación de una empresa de software?» → **corrección humana:** se ajustaron pools, lanes y compuertas a la estructura real de NubiaSoft y se verificó que las compuertas representen excepciones reales.
3. «Revisá el estilo y la claridad del texto.» → **corrección humana:** se reescribieron los párrafos para conservar la voz propia y eliminar generalidades.

**Correcciones humanas adicionales:** se verificó el significado técnico de pools, lanes, compuertas XOR y eventos; se corrigió el flujo para que ninguna factura se emita sin aprobación del cliente y de QA; se validaron los indicadores de control y la dinámica de ramas y Pull Request.

El autor asume la responsabilidad intelectual total sobre la veracidad y coherencia conceptual del contenido. El detalle ampliado está en `docs/declaracion-ia.md`.
