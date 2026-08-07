# Inmuebles Arteaga – Widget de propiedades

Este repositorio funciona como puente entre GitHub y el sitio Wix Harmony de Inmuebles Arteaga.

## Archivo principal

- `widget.js`: renderiza las dos propiedades reales, carruseles, estilos y ventana de detalles.
- `index.html`: versión independiente para pruebas.

## Código para Wix Harmony

Agregar un elemento **Embed code** y pegar:

```html
<script src="https://cdn.jsdelivr.net/gh/JCoorp/Spc@main/widget.js"></script>
```

Las imágenes se cargan directamente desde Wix Media Manager.

### Propiedades actuales

- Terreno en venta – zona Galindo (5 imágenes)
- Casa en renta – Calle Betania (19 imágenes)

Para futuras actualizaciones, modificar `widget.js`. Si el CDN conserva una versión anterior temporalmente, purgar la caché de jsDelivr o cambiar el parámetro de versión del script.