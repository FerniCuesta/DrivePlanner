# Milestones

## [M0] Milestone 0: Modelado del problema

Se busca analizar las [historias de usuario](user_stories.md) para identificar los conceptos clave del dominio del problema y plasmarlos en código.

### Entregable

Código donde estén presentes los elementos clave del dominio del problema definido en las [historias de usuario](user_stories.md) y sus interacciones. Esto incluye:

- Identificación de las entidades principales involucradas en el problema.

- Definición de las relaciones entre estas entidades.

### Viabilidad

El código entregado debe cumplir con los siguientes requisitos para ser aprobado:

- Cobertura completa del dominio del problema: El modelo debe representar todas las entidades y relaciones descritas en las historias de usuario asociadas. 

- Claridad en las relaciones: Las interacciones entre las entidades deben estar claramente especificadas y reflejar los escenarios descritos en las historias de usuario.

- Posibilidad de evolución: El diseño debe permitir la inclusión de futuras mejoras, como la automatización de la asignación de conductores basada en criterios como kilómetros recorridos o el número de viajes.

### HUs asociadas

- [HU1](user_stories.md#hu1-Mercedes-Profesora-que-quiere-conocer-los-repartos-de-coches-y-pasajeros)

## [M1] Milestone 1: Implementación de la asignación automática de conductores y pasajeros

Se busca implementar la posibilidad de asignar de forma automática conductores y pasajeros.

### Entregable

Código que permita asignar conductores y pasajeros de forma automática, en base a un algoritmo que garantice que la asignación sea equitativa y eficiente.

### Viabilidad

Cuando el código entregado pase los tests donde se compruebe que se pueden asignar conductores y pasajeros de forma automática. Además, se debe comprobar que la asignación automática es equitativa y eficiente.

### HUs asociadas

- [HU2](user_stories.md#hu2-Elisa-reparto-automático-de-coches-y-profesores)

# Milestones adicionales

## [M2] Milestone 2: Implementación de estadísticas

Se busca implementar la funcionalidad de consultar estadísticas sobre el uso de los coches.

### Entregable

Código que permita consultar estadísticas sobre el uso de los coches. 

### Viabilidad

Se considera viable cuando se pueda realizar una consulta sobre las estadísticas de los viajes.

### HUs asociadas

- [HU3](user_stories.md#hu3-Elisa-Estadísticas-sobre-los-viajes)