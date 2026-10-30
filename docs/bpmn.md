# Modelado del proceso con BPMN

## Proceso

**Gestión de proyectos y facturación de NubiaSoft Soluciones S.A.**

El proceso comienza cuando un cliente solicita una propuesta, continúa con el relevamiento de requerimientos y la elaboración del presupuesto, y finaliza con la facturación y el registro del cobro. Incluye el control de calidad del software desarrollado.

## Pools y Lanes

### Pool 1 — Cliente (actor externo)
Representa al cliente que contrata el servicio.

- **Solicitar propuesta:** el cliente envía sus requerimientos.
- **Recibir entrega y pagar:** el cliente recibe el software y abona la factura.

### Pool 2 — NubiaSoft S.A. (organización)
Contiene los roles internos y el comportamiento automatizado del sistema.

| Lane | Rol | Tareas |
| --- | --- | --- |
| **Comercial** | Área de ventas | Relevar requerimientos · Elaborar presupuesto · Crear proyecto |
| **Desarrollo** | Equipo de desarrollo | Planificar proyecto · Desarrollar módulo |
| **Calidad** | QA | Ejecutar pruebas |
| **Sistema / Administración** | Sistema automatizado y administración | Generar factura · Registrar cobro |

## Flujo estándar

1. El cliente **solicita una propuesta** con sus requerimientos.
2. Comercial **releva los requerimientos** y **elabora el presupuesto**.
3. Compuerta **XOR — ¿El cliente aprueba?**
   - **Sí:** se **crea el proyecto**.
   - **No:** se ajusta la propuesta y se vuelve a *Elaborar presupuesto* (excepción 1).
4. Desarrollo **planifica el proyecto** y **desarrolla el módulo**.
5. Calidad **ejecuta las pruebas**.
6. Compuerta **XOR — ¿Aprueba QA?**
   - **Sí:** se continúa a la facturación.
   - **No:** se corrigen los defectos y se vuelve a *Ejecutar pruebas* (excepción 2).
7. El sistema **genera la factura** y administración **registra el cobro**.
8. Fin del proceso.

## Compuertas de decisión y excepciones

- **XOR ¿El cliente aprueba?** controla la aceptación comercial de la propuesta.
- **XOR ¿Aprueba QA?** controla la calidad técnica antes de facturar.

Ambas compuertas implementan los caminos alternativos del proceso, garantizando que ninguna factura se emita sin la aprobación del cliente ni sin el control de calidad correspondiente.

## Diagrama

El diagrama completo se encuentra en `bpmn/diagrama-bpmn.svg` y en la Figura 1 del PDF consolidado.
