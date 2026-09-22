# Robótica 1.º de Primaria — SmartTEAM Libro 1

Plataforma estática para GitHub Pages con seguimiento visible para docente y Coordinación.

## Estado inicial
- Clases 1–3: impartidas
- Clase 4: actual
- Clases 5–35: pendientes

## Cómo mantener sincronizada la información
La plataforma NO guarda cambios solo en el navegador. Esto es intencional: para que docente y Coordinación vean exactamente lo mismo, el estado oficial vive en `data.js`.

Para actualizar una clase:
1. Abra `data.js`.
2. Busque la clase por `"id"`.
3. Cambie `"status"` a `impartida`, `actual` o `pendiente`.
4. Complete `execution.date`, `execution.completed`, `execution.pending` y `execution.notes`.
5. Haga commit del cambio en GitHub.

GitHub Pages publicará la misma versión para todos.

## Publicar en GitHub Pages
1. Cree un repositorio nuevo.
2. Suba `index.html` y `data.js` a la raíz.
3. Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main` / root.
6. Guarde y espere a que aparezca el enlace público.

## Nota académica
La secuencia base procede del archivo SmartTEAM Libro 1. Los encuentros que venían sin contenido en el archivo original están identificados como consolidación/adaptación docente y no se presentan como contenido oficial de SmartTEAM.

Cortesía de SolunieCloud Studio.
