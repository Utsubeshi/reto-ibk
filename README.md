# Desafío de Programación - Gestión de Superhéroes (Backend)
## Contexto del Desafío :superhero: :superhero_woman:
Has sido contratado por la organización ficticia "SuperHeroIBK" para desarrollar un sistema de gestión de superhéroes, enfocándote únicamente en el backend. El sistema debe permitir a los usuarios realizar las siguientes operaciones:

#### Crear un Superhéroe:

Un superhéroe debe tener un nombre, una descripción y una clasificación de poder (por ejemplo, bajo, medio, alto).
Debe almacenarse en la base de datos en una tabla llamada "Superheroes".
Listar Superhéroes:

Los usuarios deben poder ver una lista de todos los superhéroes almacenados en la tabla "Superheroes".

#### Actualizar un Superhéroe:

Los usuarios deben poder actualizar el nombre, la descripción o la clasificación de poder de un superhéroe existente.

#### Eliminar un Superhéroe:

Los usuarios deben poder eliminar un superhéroe de la tabla "Superheroes".

#### Crear una Habilidad:

Crea una tabla llamada "Habilidades" que tenga un campo para el nombre de la habilidad y un nivel de poder asociado.
Los usuarios deben poder crear una nueva habilidad y asociarla a un superhéroe existente.

#### Listar Habilidades de un Superhéroe:

Los usuarios deben poder ver la lista de habilidades asociadas a un superhéroe específico.

#### Actualizar una Habilidad:

Los usuarios deben poder actualizar el nombre o el nivel de poder de una habilidad existente.

#### Eliminar una Habilidad:

Los usuarios deben poder eliminar una habilidad de la base de datos. (Nota: Debes considerar las opciones de integridad referencial).

#### Buscar Superhéroes por Nombre:

Los usuarios deben poder buscar superhéroes por su nombre. El sistema debe devolver una lista de superhéroes cuyos nombres coincidan parcial o completamente con el término de búsqueda.

#### Filtrar Superhéroes por Nivel de Poder:

Los usuarios deben poder filtrar la lista de superhéroes por nivel de poder (por ejemplo, bajo, medio, alto). Deben poder seleccionar un nivel de poder y obtener la lista de superhéroes que tienen ese nivel.

## Requerimientos Técnicos
Utiliza Java y Spring Framework para desarrollar la aplicación.
Utiliza SQL Server como base de datos para almacenar la información de superhéroes y habilidades.
Implementa controladores de Spring que gestionen las operaciones CRUD para superhéroes y habilidades.
Asegúrate de que las habilidades estén relacionadas correctamente con los superhéroes en la base de datos.

## Evaluación
Serán evaluados en función de su capacidad para:

- Diseñar y crear una base de datos SQL Server que contenga dos tablas relacionadas (Superheroes y Habilidades).
- Crear una aplicación Java utilizando Spring que gestione las operaciones CRUD para ambas tablas.
- Diseñar y mantener relaciones adecuadas entre las tablas en la base de datos.
- Gestionar errores y excepciones de manera adecuada.
- Escribir código limpio y legible, se debe utilizar ingles para el codigo y las tablas
- Utilizar buenas prácticas de programación en Java y Spring.

Este desafío ahora incluye la búsqueda y el filtrado de superhéroes, así como la consideración de la integridad referencial al eliminar habilidades, lo que lo hace más completo y desafiante, es importante que tengan esto en cuenta!
