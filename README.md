# Julian Assange — Dossier

Landing page conmemorativa e informativa sobre la vida de Julian Assange: su origen, la fundación de WikiLeaks, las grandes filtraciones (Collateral Murder, Cablegate, Vault 7...), su persecución legal y su legado.

## Por qué se creó

La historia de Assange atraviesa temas centrales para cualquiera interesado en tecnología y seguridad: cifrado, protección de fuentes, filtraciones masivas de datos y el choque entre transparencia y poder. Este proyecto nació como ejercicio de diseño web para contar esa historia con una estética visual coherente con el propio tema: la de un centro de datos y un expediente clasificado, en vez de una página informativa convencional.

## Estética

- **Glassmorphism ("glass liquid")**: paneles translúcidos con `backdrop-filter: blur`, bordes con degradado sutil y reflejos internos.
- **Data center / expediente clasificado**: grid de fondo tipo blueprint, scanlines animadas, ruido de textura, paneles de terminal con logs simulados y una ficha de identificación tipo HUD para el retrato.
- **Scroll suave**: `scroll-behavior: smooth` más animaciones de aparición progresiva (`IntersectionObserver`) al recorrer las secciones.

## Estructura

```
index.html       Contenido y estructura de la página
styles.css        Estilos (glassmorphism, animaciones, layout responsive)
assets/           Imágenes (retrato de Julian Assange)
```

## Créditos

La fotografía del retrato proviene de Wikimedia Commons (autoría: Julian Assange & Martina Haris), publicada en dominio público.

## Uso

Es una página estática, sin dependencias ni build. Basta con abrir `index.html` en el navegador, o servirla localmente:

```
python3 -m http.server 8000
```
