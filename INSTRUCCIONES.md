# 📲 Leche Barista — Instalar como App Android

## Archivos incluidos
```
index.html      ← La app principal
manifest.json   ← Le dice a Chrome que es una PWA instalable
sw.js           ← Permite usarla sin internet (offline)
icon-192.png    ← Ícono para el cajón de apps
icon-512.png    ← Ícono en alta resolución
```

---

## Paso 1 — Subir a GitHub Pages (1 vez)

1. Entrá a **github.com** desde tu PC
2. Click en **"New repository"** (botón verde)
3. Nombre: `leche-barista` · Marcá **Public** · Click **Create**
4. Abrí el repo recién creado → click en **"uploading an existing file"**
5. **Arrastrá los 5 archivos** de esta carpeta al área de carga
6. Click **"Commit changes"**
7. Ir a **Settings → Pages**
8. En "Branch" elegí **main** y carpeta **/ (root)** → Click **Save**
9. Esperá ~1 minuto → aparece la URL: `https://TU-USUARIO.github.io/leche-barista`

---

## Paso 2 — Instalar en el Galaxy Fold 4

1. Abrí **Chrome** en el teléfono
2. Navegá a tu URL: `https://TU-USUARIO.github.io/leche-barista`
3. Aparece un **banner azul** en la app que dice "Instalá como app" → tap **Instalar**
   - Si no aparece el banner: menú Chrome (3 puntos) → **"Agregar a pantalla de inicio"**
4. Confirmá → la app aparece en el cajón de aplicaciones como cualquier otra app

---

## ✅ Resultado final
- Ícono propio en el cajón de apps
- Se abre en pantalla completa (sin barra de Chrome)
- **Funciona sin internet** (el service worker guarda todo en caché)
- Para actualizar la app: editá el `index.html` en GitHub → los cambios se aplican solos

---

## Actualizar la app en el futuro
Si querés modificar algo:
1. Entrá a github.com → tu repo → click en `index.html`
2. Click el ícono del lápiz (editar)
3. Hacé los cambios → **Commit changes**
4. En el teléfono: abrí la app con internet → se actualiza sola

