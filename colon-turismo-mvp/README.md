# Colón Turismo MVP

Prototipo web inicial de una guía turística de Colón, Panamá.

## Ejecutar

Requiere Node.js 18 o superior.

``` bash
npm start
```

Abre `http://localhost:3000`. No requiere instalar dependencias npm: el
servidor usa módulos integrados de Node.js.

## Incluye

-   Diseño adaptable a móvil y escritorio.
-   Catálogo de demostración.
-   Búsqueda y filtros por categoría.
-   Mapa interactivo con marcadores.
-   Geolocalización bajo permiso explícito del usuario.
-   Fichas informativas y enlaces para consultar direcciones.
-   Sección informativa para la futura función AR.

## Limitaciones

-   Las ubicaciones son aproximadas y deben verificarse antes de
    publicar.
-   No implementa realidad aumentada ni activa la cámara.
-   No incluye base de datos ni panel de administración.
-   Leaflet, OpenStreetMap y la imagen principal requieren conexión a
    internet.
-   En producción, la geolocalización requiere HTTPS.
-   Revisa las condiciones de uso y atribución del proveedor de mapas
    antes del lanzamiento.

## Próximos pasos

1.  Validar los nombres y coordenadas exactas de los lugares.
2.  Reemplazar imágenes provisionales por fotografías autorizadas.
3.  Probar en móviles reales.
4.  Decidir si se necesita PWA, API o panel administrativo.
5.  Evaluar AR en los dispositivos objetivo.


### Actualización de prueba realizada desde Windows.