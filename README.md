# cuadrilatero-cdn

Repo de medios para el portafolio. **No hace falta mantener manifest.json.**

El CRM lista este repo con la API pública de GitHub y sirve los archivos vía jsDelivr.

## Setup

1. Crea el repo **público** (ej. `cuadrilatero-cdn`).
2. Sube imágenes/PDF en carpetas, por ejemplo:

```
projects/nexa/cover.webp
projects/nexa/manual.pdf
agentex/char-01.webp
```

3. En el CRM → Ajustes → Base CDN:

```
https://cdn.jsdelivr.net/gh/TU_USUARIO/cuadrilatero-cdn@main/
```

4. Galería → pestaña CDN → **Listar archivos del repo**.

## URLs generadas

`https://cdn.jsdelivr.net/gh/TU_USUARIO/cuadrilatero-cdn@main/projects/nexa/cover.webp`

## Notas

- Repo debe ser **público**.
- GitHub API tiene rate limit sin token (~60 req/hora por IP); para uso normal del CMS sobra.
- `manifest.json` es opcional (solo fallback).
