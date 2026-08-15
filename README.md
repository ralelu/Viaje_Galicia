# Galicia 2026 · Del cañón al Atlántico

Web estática con el itinerario completo del viaje (21–27 de agosto de 2026):

- `index.html` — la guía completa: itinerario día a día, información cultural de cada parada, guía de furanchos y carnes, y checklist de reservas.
- `infografia-ribeira-sacra.html` — infografía vertical de la etapa 1 (21–22 ago).
- `infografia-rias-baixas.html` — infografía vertical de la etapa 2 (23–27 ago).

No hay dependencias ni build: solo HTML y CSS (tipografías de Google Fonts).

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `viaje-galicia`).
2. Sube estos archivos a la raíz del repositorio:
   ```bash
   git init
   git add .
   git commit -m "Itinerario Galicia 2026"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/viaje-galicia.git
   git push -u origin main
   ```
3. En GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En un par de minutos la web estará en `https://TU_USUARIO.github.io/viaje-galicia/`.

## Consejos

- Las infografías están pensadas para verse en el móvil o imprimirse (tienen estilos de impresión).
- Para guardarlas como imagen: abrirlas en el móvil y hacer captura larga, o en el ordenador imprimir → guardar como PDF.
