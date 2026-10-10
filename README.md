# tinybuddy — tu compañero digital (PWA)

Mascota virtual con monedas, tienda, inventario, minijuegos, niveles, logros y modo offline.

## Archivos

```
index.html              App principal
manifest.webmanifest    Manifiesto PWA
sw.js                   Service Worker (offline)
icons/                  Iconos de instalación
README.md               Este archivo
```

## Cómo publicarlo en GitHub

### Opción A — Subir archivos sueltos (recomendado)
1. Crea un repositorio nuevo en GitHub.
2. Descomprime este ZIP en tu PC.
3. En GitHub: **Add file → Upload files** y arrastra **todo el contenido** de la carpeta (no el ZIP).
4. Commit.

### Opción B — GitHub Pages (para jugar online + instalar PWA)
1. En el repo: **Settings → Pages → Source: Deploy from branch → main / root**.
2. Abre `https://TU-USUARIO.github.io/TU-REPO/`.
3. En el móvil podrás **Instalar app** y usarla sin conexión.

### Opción C — Línea de comandos
```bash
unzip tinybuddy-pwa.zip -d tinybuddy
cd tinybuddy
git init
git add .
git commit -m "tinybuddy PWA"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

## Probar en local
```bash
python3 -m http.server 8080
# Abre http://localhost:8080
```

> El modo offline e instalar app solo funcionan por **http/https**, no abriendo el HTML como archivo.

## Controles (PC)
| Tecla | Acción |
|-------|--------|
| 1 | Comer (inventario) |
| 2 | Jugar |
| 3 | Limpiar |
| 4 | Descansar |
| 5 | Acariciar / regalos |
| 6 | Tienda |
| Esc | Cerrar modal |
