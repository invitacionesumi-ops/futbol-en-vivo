# Fútbol en Vivo - Web

Página web responsive equivalente al proyecto Android.

## Archivos
- index.html
- streams.json

## Uso
Abrí `index.html` desde un hosting o GitHub Pages.

Para cambiar partidos, editá `streams.json`.

Ejemplo:

```json
{
  "name": "Argentino de Rosario vs Defensores de Glew",
  "competition": "Primera C",
  "time": "15:30",
  "url": "https://servidor.com/playlist.m3u8"
}
```

## GitHub Pages
1. Crear repositorio.
2. Subir `index.html` y `streams.json`.
3. Settings > Pages.
4. Deploy from branch.
5. Seleccionar `main` y `/root`.

## Importante
El navegador puede bloquear algunos streams si el servidor no permite CORS o exige autenticación, cookies, Referer u Origin específicos.
