# Cena del Viernes

Un restaurante al mes para cenar un viernes en Madrid, Alcalá de Henares, Torrejón de Ardoz, Cobeña y Daganzo de Arriba, con cubierto medio de 45 € o menos y buenas críticas.

- `index.html`: la app (funciona en cualquier navegador; en el móvil, «Añadir a pantalla de inicio»).
- `restaurantes.json`: los datos. Una rutina semanal de Claude añade restaurantes nuevos cada lunes (campo `alta` = fecha de alta).
- `estado.json`: restaurantes ya visitados (`fuimos`: id → fecha) o descartados (`no`: id → true) para todos los móviles. La propuesta no cambia hasta que la actual aparece aquí o se marca en el propio móvil.
