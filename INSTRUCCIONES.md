# Turno Colegio — Instrucciones de despliegue

## Archivos incluidos
- index.html — la app completa
- manifest.json — configuración PWA
- sw.js — service worker (funciona sin internet)
- icon-192.png y icon-512.png — agregar íconos manualmente

## Cómo subir a Vercel (gratis, sin programar)

1. Ve a https://vercel.com y crea una cuenta gratis (puedes entrar con Google)
2. Click en "Add New Project"
3. Elige "Browse" o arrastra la carpeta turno-colegio completa
4. Vercel detecta automáticamente que es un sitio estático
5. Click en "Deploy"
6. En 1 minuto tendrás una URL tipo: https://turno-colegio.vercel.app

## Cómo lo instalan las mamás en el celular

### iPhone (Safari):
1. Abrir la URL en Safari
2. Tocar el botón compartir (cuadrado con flecha)
3. "Agregar a pantalla de inicio"
4. Aparece como app con ícono verde

### Android (Chrome):
1. Abrir la URL en Chrome
2. Aparece un banner automático "Instalar app"
3. O bien: menú ⋮ → "Agregar a pantalla de inicio"

## Configuración de Firebase (ya incluida en el código)
El código ya tiene las credenciales de tu proyecto Turno-Colegio configuradas.
Los datos se sincronizan en tiempo real entre todos los celulares.

## Íconos
Agregar dos imágenes PNG con el ícono de la app:
- icon-192.png (192x192 píxeles)
- icon-512.png (512x512 píxeles)
Puedes crear íconos gratis en https://favicon.io
