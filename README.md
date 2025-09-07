#  Sistema de Gestión de Biblioteca Digital

Proyecto en **Java** que implementa un sistema simple de gestión de biblioteca aplicando colecciones (`List`, `Set`, `Map`) y principios de Programación Orientada a Objetos (POO).

## Funcionalidades

- **Gestión de libros**
  - Añadir / Quitar libros
  - Buscar por título, autor o categoría  

- **Gestión de usuarios**
  - Registrar / Dar de baja usuarios  

- **Préstamos**
  - Prestar / Devolver libros  
  - Listar los libros prestados por un usuario  

#  Clases

- **Libro**  
  Representa un libro inmutable con atributos `isbn`, `titulo`, `autor`, `categoria`.  

- **Usuario**  
  Representa a un usuario con `id`, `nombre` y una lista de ISBNs de los libros prestados.  

- **Biblioteca**  
  Administra los mapas de libros y usuarios, así como el conjunto de ISBNs prestados.  

- **Main**  
  Clase de prueba con un flujo de ejemplo.  


