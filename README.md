# Dynamic ORM database system.
Sistema que analiza el una base de datos y las combierte en un script de Javascript.

## Propuesta de funciones

### Variables de entorno
Se requiren de unas variables de entorno para que el sistema sepa a que base de datos debe atacar

- DB_TABLE
- DB_USER
- DB_PASS

### Métodos
| Nombre | Propiedades | Función |
|---|---|---|
| syncTable | Nombre de la base de datos | Analiza y crear scripts por cada tabla de la base de datos
