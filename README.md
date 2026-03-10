# Landing Page para GitHub Pages

Este paquete ya está listo para subirlo a un repositorio de GitHub y publicarlo con **GitHub Pages**.

## Archivos incluidos
- `index.html` → landing principal
- `.nojekyll` → evita procesamiento Jekyll y publica el HTML tal cual

## Cómo publicarla
1. Crea un repositorio nuevo en GitHub.
2. Sube el contenido de esta carpeta a la raíz del repositorio.
3. En GitHub entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda los cambios.
6. GitHub generará un enlace como:
   - `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

## Si quieres usar dominio propio
1. Compra o usa tu dominio.
2. En GitHub Pages configura el campo **Custom domain**.
3. Crea los registros DNS correspondientes en tu proveedor.

## Recomendación
Si quieres que la web quede directamente en:
- `https://TU-USUARIO.github.io/`

debes nombrar el repositorio exactamente así:
- `TU-USUARIO.github.io`
