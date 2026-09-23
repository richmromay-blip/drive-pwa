# Drive — PWA v1

PWA independiente para registrar efectivo, tarjeta Didi, gastos y cierre de día.

## Funciones actuales
- Registro rápido de efectivo.
- Registro único de tarjeta al final del día.
- Registro de gastos por categoría.
- Cálculo de efectivo esperado.
- Cierre de día comparando efectivo esperado vs. efectivo contado.
- Persistencia local con localStorage.
- Funcionamiento offline mediante Service Worker.
- Instalable como PWA cuando se sirve desde HTTPS (o localhost).

## Importante
Los datos se guardan localmente en el dispositivo/navegador. Esta versión no tiene sincronización en la nube.

## Archivos
- index.html
- manifest.json
- sw.js
- icon.svg
