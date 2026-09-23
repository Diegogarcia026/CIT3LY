# Requisitos del sistema de biblioteca

## Funciones necesarias
1. Registrar libros con título, autor, ISBN y número de ejemplares.
2. Registrar usuarios con nombre, matrícula o credencial y correo.
3. Buscar libros por título, autor o ISBN.
4. Consultar si un libro está disponible o prestado.
5. Registrar un préstamo indicando usuario, libro y fecha.
6. Registrar la devolución y actualizar la disponibilidad del libro.
7. Consultar el historial de préstamos de cada usuario.

## Reglas iniciales para los préstamos
- Cada usuario puede tener máximo 3 libros prestados al mismo tiempo.
- El préstamo dura 7 días naturales.
- Se puede renovar una sola vez, si nadie más apartó el libro.
- No se presta un libro si no hay ejemplares disponibles.
- Un usuario con libros vencidos no puede pedir otro préstamo hasta devolverlos.
- Solo el personal de la biblioteca registra préstamos y devoluciones.
