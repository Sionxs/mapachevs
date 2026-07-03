# Mapache vs Monstruos

Juego arcade en HTML5/JavaScript puro (sin dependencias). Listo para desplegar en Vercel.

## Opción 1: Arrastrar y soltar (la más rápida, sin instalar nada)

1. Entra a https://vercel.com y crea una cuenta gratis (puede ser con GitHub, Google, etc.).
2. En el dashboard, busca la opción de subir un proyecto manualmente ("Add New" -> "Project" -> pestaña para importar/subir una carpeta) o usa https://vercel.com/new y arrastra esta carpeta completa.
3. Vercel detecta que es un sitio estático automáticamente. Dale a "Deploy".
4. En segundos te da una URL pública tipo `https://tu-proyecto.vercel.app` donde el juego ya es jugable.

## Opción 2: Con la CLI de Vercel (si tienes Node.js instalado)

Desde una terminal, parado dentro de esta carpeta:

```bash
npm install -g vercel
vercel login
vercel --prod
```

Sigue las instrucciones en pantalla (nombre del proyecto, confirmar carpeta, etc.) y al final te entrega la URL pública.

## Opción 3: Subir a GitHub y conectar el repo

1. Crea un repositorio en GitHub y sube estos archivos (`index.html`, `vercel.json`).
2. En Vercel, "Add New" -> "Project" -> "Import Git Repository" y selecciona el repo.
3. Deploy automático. Cada vez que hagas push a GitHub, Vercel actualiza el sitio solo.

## Archivos incluidos

- `index.html` — el juego completo (HTML + CSS + JS en un solo archivo).
- `vercel.json` — configuración mínima para que Vercel lo sirva como sitio estático.
