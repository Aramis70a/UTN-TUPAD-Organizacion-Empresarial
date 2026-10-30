# Declaración de Uso de IA

## Herramienta utilizada

Asistente de IA generativa (modelo de lenguaje) para apoyo en la redacción, la organización documental y la propuesta de diseño del diagrama BPMN.

## Prompts utilizados (resumen crítico)

1. **"Proponé la estructura de un TPI de Organización Empresarial con BPMN, Git/GitHub y backlog ágil."**
   - *Uso:* obtener un índice inicial. *Corrección humana:* se descartaron secciones que no correspondían a la consigna y se respetó el orden pedido por la cátedra.

2. **"¿Cómo modelar en BPMN el proceso de gestión de proyectos y facturación de una empresa de software?"**
   - *Uso:* ideas de pools, lanes y compuertas. *Corrección humana:* se ajustaron los roles a la estructura real de NubiaSoft y se verificó que las compuertas representen excepciones reales (rechazo del cliente y rechazo de QA).

3. **"Revisá el estilo y la claridad del texto."**
   - *Uso:* corrección de estilo. *Corrección humana:* se reescribieron los párrafos para conservar la voz propia y se eliminaron generalidades.

## Correcciones humanas realizadas

- Se verificó que cada concepto (pool, lane, compuerta XOR, evento) se use con su significado técnico correcto.
- Se corrigió el flujo para que ninguna factura se emita sin aprobación del cliente y de QA.
- Se revisaron los indicadores de control para que sean medibles y verificables.
- Se validó la dinámica de ramas y PR descrita en `docs/git-workflow.md`.

## Responsabilidad

El autor asume la responsabilidad intelectual total sobre el contenido. La IA se utilizó como herramienta de apoyo y no reemplaza el criterio propio ni la verificación conceptual.
