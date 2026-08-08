# cuadrilatero-cdn

Repo de medios para el portafolio (imágenes, PDF).

## Uso con jsDelivr

1. Sube archivos a este repo (público).
2. Mantén `manifest.json` actualizado con `path` relativos.
3. En el CRM → Ajustes → CDN base:

```
https://cdn.jsdelivr.net/gh/TU_USUARIO/cuadrilatero-cdn@main/
```

4. En la galería del CMS → pestaña CDN → Cargar manifest.

Las URLs resultantes serán tipo:
`https://cdn.jsdelivr.net/gh/TU_USUARIO/cuadrilatero-cdn@main/projects/ejemplo/cover.webp`
