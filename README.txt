# GRTEC WebAR - Coffee 3D

Archivos:

- index.html
- assets/Coffee3d.glb
- assets/marker.png
- assets/coffee-marker.mind  <-- debes generarlo con MindAR

## Generar el marcador

1. Abre el compilador oficial de MindAR:
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Sube `assets/marker.png`.
3. Pulsa Start.
4. Descarga el archivo `.mind`.
5. Renómbralo a `coffee-marker.mind`.
6. Colócalo dentro de `assets/`.

Después ejecuta el proyecto mediante un servidor HTTPS o un servidor local.

El modelo Coffee3d.glb aparece al reconocer el marcador, entra con una animación de escala, gira y flota suavemente.
