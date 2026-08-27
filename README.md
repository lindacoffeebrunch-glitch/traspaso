# LINDA · Landing de transmisión

Landing pública estática para el proceso privado de transmisión de LINDA Specialty Coffee & Brunch en Valdemoro.

## Arquitectura

- `index.html`: contenido, estructura semántica y estilos de la landing.
- `assets/images/`: fotografías reales optimizadas para la web.

El proyecto no utiliza frameworks, paquetes ni dependencias externas. Puede publicarse directamente con GitHub Pages cuando se decida activar la publicación.

## Imágenes

Las fotografías están integradas en formato WebP con estos nombres:

- `assets/images/linda-hero.webp`
- `assets/images/linda-local.webp`
- `assets/images/linda-operacion.webp`
- `assets/images/linda-marca.webp`

El hero utiliza una vista general de la barra y las otras tres imágenes documentan el espacio, la operación y la marca. Todas mantienen proporciones estables y los recursos situados bajo el primer bloque se cargan de forma diferida.

## Prueba local

Puedes abrir `index.html` directamente en un navegador. Para probarlo mediante un servidor local desde la raíz del repositorio:

```bash
python3 -m http.server 8000
```

Después visita `http://localhost:8000`.

## Publicación futura

La web está preparada para GitHub Pages con rutas relativas. GitHub Pages no está activado como parte de esta versión.
