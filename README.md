# Library App

## Descripción
Library App es una aplicación diseñada para gestionar la colección de libros de una biblioteca. Permite a los usuarios buscar, agregar, eliminar y actualizar información sobre los libros.

## Estructura del proyecto
- src
  - controllers
    - BookController.ts
  - models
    - Book.ts
    - User.ts
  - services
    - BookService.ts
  - interfaces
    - IBook.ts
    - IUser.ts
  - utils
    - Logger.ts
- tests
  - BookController.test.ts
  - BookService.test.ts
- README.md
- package.json
- tsconfig.json

## Clases e interfaces clave
- **BookController**: Controlador que maneja las solicitudes relacionadas con los libros.
- **BookService**: Servicio que contiene la lógica de negocio para la gestión de libros.
- **Book**: Modelo que representa un libro.
- **User**: Modelo que representa un usuario.
- **IBook**: Interfaz que define la estructura de un libro.
- **IUser**: Interfaz que define la estructura de un usuario.
- **Logger**: Utilidad para el registro de logs.

## Uso
1. Clona el repositorio:  
   