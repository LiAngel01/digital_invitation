# Invitación de Natalia

Invitación estática, en español y adaptable a celulares. No requiere dependencias.

## Personalizar

- Edita `index.html` para cambiar los textos y agregar fecha, hora y dirección en la sección "Los detalles".
- Las tres fotos JPEG deben permanecer junto a `index.html`; la portada y la galería las cargan desde esa carpeta.
- Para reemplazar una foto, conserva su nombre o actualiza su ruta en `index.html`.

## Publicación

El repositorio usa el flujo de GitHub Actions en `.github/workflows/deploy.yml`. Los cambios que subas a `main` se publican automáticamente en:

https://liangel01.github.io/digital_invitation/

Para subir actualizaciones desde una terminal, dentro de la carpeta del proyecto:

```powershell
git add index.html README.md ".\WhatsApp Image 2026-10-25 at 9.18.21 PM.jpeg" ".\WhatsApp Image 2026-10-25 at 9.18.22 PM (1).jpeg" ".\WhatsApp Image 2026-10-25 at 9.18.22 PM.jpeg"
git commit -m "Update Natalia's invitation"
git push
```

El repositorio es público: el contenido del sitio y las fotos subidas a GitHub podrán ser vistos por otras personas. La disponibilidad del enlace desde Cuba depende de la conexión y conviene probarlo desde allí.
