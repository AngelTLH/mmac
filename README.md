# MMAC | Agencia Comunicacional Sustentable

Sitio web interactivo desarrollado con React y Vite para MMAC, basado en la maqueta `documentacion/MMAC_PAGINA_WEB.pdf` y en el concepto de agencia comunicacional sustentable de `documentacion/MMAC__AGENCIA_COMUNICACIONAL.pdf`.

## Desarrollo local

```bash
npm install
npm run dev
```

## Build de producción

```bash
npm run build
```

## GitHub Pages

La configuración usa `base: './'` en `vite.config.js` para que los assets funcionen correctamente cuando el sitio se publique desde GitHub Pages en una ruta de repositorio. También se incluye `.nojekyll` y un script de despliegue con `gh-pages`:

```bash
npm run deploy
```
