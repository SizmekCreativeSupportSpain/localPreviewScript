# <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/HTML5.png" alt="Sizmek" width="26" height="36" /></a> localPreview.js <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/logo-dark.png" alt="Sizmek" width="57" height="15" /></a>

Con este script podrás probar los formatos de sizmek en local, evitando problemas de dependencia de funciones y variables necesarias para servir la creatividad en real.

## Descripción

Este script simplemente genera los objetos de adServing de Sizmek para evitar errores en consola.

## Configuración 

Para utilizar este script, simplemente añade este codigo dentro de tu javascript, despues de que se haya cargado completamente el DOM( cuando se haya lanzado el evento document.load ).

```javascript
try {
	if (window.localPreview) {
	    window.initializeLocalPreview();
	}
}
catch (e) {}
```

Recuerda que debes tambien cargar el script dentro del fichero html donde se vaya a utilizar:

```html
<script type="text/javascript" src="https://services.serving-sys.com/custprojassets/prd/features/feeds/1884/localPreview.js"></script>
```

Cuando hayas terminado con las pruebas en local, es recomendable eliminar todas las referencias a la libreria tanto del HTML como de los ficheros javascript donde se este cargando.

Recuerda que si tienes cualquier duda puedes ponerte en contacto con el equipo de <a href="mailto:creativesupport-spain@sizmek.com">Soporte Creativo de Sizmek</a>

***