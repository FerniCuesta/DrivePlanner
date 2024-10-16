# Milestones

## [M0] Milestone 0: Modelado del problema

Se busca analizar las [historias de usuario](user_stories.md) para identificar los conceptos clave del dominio del problema y plasmarlos en código.

### Entregable

Un modelo conceptual del sistema que represente los elementos clave del dominio y sus interacciones. Esto incluye:
- Identificación de las entidades principales involucradas en el problema, tales como profesores, puntos de encuentro y asignaciones.

- Definición de las relaciones entre estas entidades, como la asignación de profesores a conductores o pasajeros.

- Un diseño estructurado que permita sentar las bases para la futura implementación de estas entidades en código.

Este modelo conceptual no debe centrarse en la implementación exacta (clases y atributos específicos), sino en la creación de una estructura flexible que guíe las decisiones de implementación en los siguientes hitos.

### Viabilidad

El modelo conceptual debe cumplir con los siguientes requisitos para ser aprobado:

- Cobertura completa del dominio del problema: El modelo debe representar todas las entidades y relaciones descritas en las historias de usuario asociadas. Las entidades clave, como los profesores, puntos de encuentro y asignaciones, deben estar claramente definidas, junto con sus relaciones.

- Claridad en las relaciones: Las interacciones entre las entidades (por ejemplo, la asignación de un profesor a un coche o la relación entre un punto de encuentro y los trayectos) deben estar claramente especificadas y reflejar los escenarios descritos en las historias de usuario.

- Posibilidad de evolución: El diseño debe permitir la inclusión de futuras mejoras, como la automatización de la asignación de conductores basada en criterios como kilómetros recorridos o el número de viajes.

### HUs asociadas

- [HU1](user_stories.md#hu1-profesor-conductor)
- [HU2](user_stories.md#hu2-profesor-pasajero)
- [HU3](user_stories.md#hu3-administrador-asignacion-manual-de-conductores-y-pasajeros)
- [HU4](user_stories.md#hu4-administrador-asignacion-automatica-de-conductores-y-pasajeros)
- [HU5](user_stories.md#hu5-administrador-estadisticas)
- [HU6](user_stories.md#hu6-profesor-notificaciones)

## [M1] Milestone 1: Implementación de la asignación manual de conductores y pasajeros

Implementar la funcionalidad de asignación manual de conductores y pasajeros.

### Entregable

Código que permita crear, modificar y consultar la asignación manual de conductores y pasajeros.

### Viabilidad

Cuando el código pase los tests donde se compruebe que se pueden crear, modificar y consultar asignaciones manuales de conductores y pasajeros.

### HUs asociadas

- [HU3](user_stories.md#hu3-administrador-asignacion-manual-de-conductores-y-pasajeros)

## [M2] Milestone 2: Implementación de la asignación automática de conductores y pasajeros

Se busca implementar la posibilidad de asignar de forma automática conductores y pasajeros.

### Entregable

Código que permita asignar conductores y pasajeros de forma automática, en base a un algoritmo que garantice que la asignación sea equitativa y eficiente.

### Viabilidad

Cuando el código entregado pase los tests donde se compruebe que se pueden asignar conductores y pasajeros de forma automática. Además, se debe comprobar que la asignación automática es equitativa y eficiente.

### HUs asociadas

- [HU4](user_stories.md#hu4-administrador-asignacion-automatica-de-conductores-y-pasajeros)

## [M3] Milestone 3: Los profesores pueden consultar si les toca llevar el coche

Un profesor debe ser capaz de comprobar si le toca llevar el coche, y en caso afirmativo, qué pasajeros le han sido asignados, a qué hora debe recogerlos y en qué punto de encuentro.

### Entregable

Código que permita a un profesor consultar la información necesaria para organizar el viaje. Es decir, saber si le toca llevar el coche y, en caso afirmativo, qué pasajeros le han sido asignados, a qué hora debe recogerlos y en qué punto de encuentro.

### Viabilidad

Cuando los tests de aceptación comprueben que se puede consultar la información necesaria para organizar el viaje.

### HUs asociadas

- [HU1](user_stories.md#hu1-profesor-conductor)

## [M4] Milestone 4: Los profesores pueden consultar si les toca ser pasajeros

Un profesor debe ser capaz de comprobar si le toca ser pasajero, y en caso afirmativo, quién es el conductor, a qué hora debe estar en el punto de encuentro y qué otros pasajeros le acompañarán.

### Entregable

Código que permita a un profesor consultar la información necesaria para ser recogido como pasajero.

### Viabilidad

Cuando los tests de aceptación comprueben que se puede consultar la información necesaria para ser recogido como pasajero.

### HUs asociadas

- [HU2](user_stories.md#hu2-profesor-pasajero)

# Milestones adicionales

## [M5] Milestone 5: Estadísticas

Se busca implementar la funcionalidad de consultar estadísticas sobre el uso de los coches.

### Entregable

Código que permita consultar estadísticas sobre el uso de los coches. Por ejemplo, cuántos kilómetros ha conducido cada profesor, cuántos días ha llevado el coche, cuántos días ha sido pasajero, etc.

### Viabilidad

Cuando los tests de aceptación comprueben que se pueden consultar las estadísticas sobre el uso de los coches.

### HUs asociadas

- [HU5](user_stories.md#hu5-administrador-estadisticas)

## [M6] Milestone 6: Notificaciones

Se buscar implementar la funcionalidad de notificaciones. 

### Entregable

Código que permita enviar notificaciones a los profesores. Los profesores deben recibir notificaciones cuando les toque llevar el coche o ser pasajeros. Deben poder configurar las notificaciones para que les lleguen a una hora concreta del día anterior.

### Viabilidad

Cuando los tests de aceptación comprueben que se pueden enviar notificaciones a los profesores.

### HUs asociadas

- [HU6](user_stories.md#hu6-profesor-notificaciones)