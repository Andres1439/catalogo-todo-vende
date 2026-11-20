# TODOVENDE – Catálogo de zapatillas

Catálogo web de zapatillas (Mujer / Hombre) con filtro por talla y pedido directo por WhatsApp.

## Estructura
```
index.html      ← la página (abre esta)
img/            ← fotos del catálogo de Canva
img/sk/         ← fotos oficiales por modelo
```
**Importante:** `index.html` y la carpeta `img/` siempre deben ir juntos.

## Publicar con GitHub Pages
1. Sube el contenido de esta carpeta a un repositorio (index.html en la raíz).
2. En el repositorio: **Settings → Pages → Branch: main / (root) → Save**.
3. En 1–2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Editar productos, precios o WhatsApp
Todo está al inicio del `<script>` en `index.html`, en el bloque `CONFIGURA AQUÍ`:
- `WHATSAPP`: número con código de país (51…).
- `PRODUCTS`: cada zapatilla con `code`, `desc` (color), `price` (`null` = "Consultar"), `sizes` e `imgs`.
