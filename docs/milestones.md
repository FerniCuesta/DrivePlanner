# Milestones

## [M0] Milestone 0: Modelado del problema

### Objetivo

Analizar las [historias de usuario](user_stories.md) para identificar los conceptos clave del dominio del problema y plasmarlos en código.

### Entregable

Código que modele los conceptos clave del dominio del problema.

### Viabilidad

Cuando sea aprobado por el product manager (los compañeros de clase y el profesor).

### HUs asociadas

- [HU1](user_stories.md#hu1-profesor-conductor)
- [HU2](user_stories.md#hu2-profesor-pasajero)
- [HU3](user_stories.md#hu3-administrador-asignacion-manual-de-conductores-y-pasajeros)
- [HU4](user_stories.md#hu4-administrador-asignacion-automatica-de-conductores-y-pasajeros)
- [HU5](user_stories.md#hu5-administrador-estadisticas)
- [HU6](user_stories.md#hu6-profesor-notificaciones)

## [M1] Milestone 1: Implementación de la asignación manual de conductores y pasajeros

### Objetivo

Implementar la funcionalidad de asignación manual de conductores y pasajeros.

### Entregable

Código que permita crear, modificar y consultar la asignación manual de conductores y pasajeros.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU3](user_stories.md#hu3-administrador-asignacion-manual-de-conductores-y-pasajeros)

## [M2] Milestone 2: Implementación de la asignación automática de conductores y pasajeros

### Objetivo

Implementar la funcionalidad de asignación automática de conductores y pasajeros. Esta asignación debe ser equitativa y tener en cuenta la disponibilidad de los profesores.

### Entregable

Código que permita asignar conductores y pasajeros de forma automática.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU4](user_stories.md#hu4-administrador-asignacion-automatica-de-conductores-y-pasajeros)

## [M3] Milestone 3: Los profesores pueden consultar si les toca llevar el coche

### Objetivo

Implementar la funcionalidad de consulta de si a un profesor le toca llevar el coche, y en caso afirmativo, qué pasajeros le han sido asignados, a qué hora debe recogerlos y en qué punto de encuentro.

### Entregable

Código que permita a un profesor consultar la información necesaria para organizar el viaje. Es decir, saber si le toca llevar el coche y, en caso afirmativo, qué pasajeros le han sido asignados, a qué hora debe recogerlos y en qué punto de encuentro.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU1](user_stories.md#hu1-profesor-conductor)

## [M4] Milestone 4: Los profesores pueden consultar si les toca ser pasajeros

### Objetivo

Implementar la funcionalidad de consulta de si a un profesor le toca ser pasajero, y en caso afirmativo, quién le recogerá y a qué hora debe estar en el punto de encuentro acordado.

### Entregable

Código que permita a un profesor consultar la información necesaria para ser recogido como pasajero.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU2](user_stories.md#hu2-profesor-pasajero)

# Milestones adicionales

## [M5] Milestone 5: Estadísticas

### Objetivo

Implementar la funcionalidad de consulta de estadísticas sobre el uso de los coches. Se debe poder consultar cuántos días ha llevado el coche cada profesor y cuántos días ha sido pasajero.

### Entregable

Código que permita consultar estadísticas sobre el uso de los coches.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU5](user_stories.md#hu5-administrador-estadisticas)

## [M6] Milestone 6: Notificaciones

### Objetivo

Implementar la funcionalidad de notificaciones. Los profesores deben recibir notificaciones cuando les toque llevar el coche o ser pasajeros. Deben poder configurar las notificaciones para que les lleguen a una hora concreta del día anterior.

### Entregable

Código que permita enviar notificaciones a los profesores.

### Viabilidad

Cuando los tests de aceptación de las historias de usuario asociadas a esta funcionalidad pasen correctamente.

### HUs asociadas

- [HU6](user_stories.md#hu6-profesor-notificaciones)