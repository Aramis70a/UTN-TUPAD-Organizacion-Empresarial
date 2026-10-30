# Mecanismos de control y estándares de desempeño

## Indicadores de control (KPI)

| Indicador | Estándar de desempeño | Frecuencia |
| --- | --- | --- |
| Proyectos entregados en fecha | ≥ 90 % | Mensual |
| Tiempo de propuesta a aprobación | ≤ 5 días hábiles | Por propuesta |
| Defectos detectados post-entrega | ≤ 2 % de los casos | Por entrega |
| Días promedio de cobro | ≤ 30 días | Mensual |
| Horas registradas vs. estimadas | Entre 95 % y 105 % | Por proyecto |
| Cobertura de pruebas automatizadas | ≥ 80 % del código crítico | Por release |

## Estándares de desempeño técnico

- **Revisión de código:** todo cambio se integra mediante Pull Request con revisión de pares.
- **Calidad:** ninguna funcionalidad se considera terminada sin pruebas y aprobación de QA.
- **Documentación:** cada módulo actualiza su documentación técnica en el repositorio.
- **Trazabilidad:** cada tarea está vinculada a una Historia de Usuario y a un *issue*.
- **Seguridad:** control de accesos por rol y registro de auditoría de operaciones sensibles.

## Auditoría técnica

La auditoría se realiza sobre el repositorio (historial de commits, ramas y PR) y sobre el tablero ágil (estado de las Historias de Usuario). Los desvíos respecto de los estándares generan una acción correctiva registrada en el tablero.
