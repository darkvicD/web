# NEXUS — Torneos de Videojuegos 🎮

Plataforma oscura de torneos para Mario Kart, Valorant, Street Fighter y más.

## ¿Cómo subir a GitHub Pages?

### Paso 1 — Crea el repositorio
1. Ve a [github.com/new](https://github.com/new)
2. Ponle el nombre que quieras (ej: `nexus-torneos`)
3. Márcalo como **Public**
4. Haz clic en **Create repository**

### Paso 2 — Sube el archivo
**Opción A — Desde la web (más fácil):**
1. En el repositorio recién creado, haz clic en **"uploading an existing file"**
2. Arrastra el archivo `index.html`
3. Escribe un mensaje de commit (ej: "Subir página")
4. Haz clic en **Commit changes**

**Opción B — Con Git:**
```bash
git init
git add index.html
git commit -m "Subir página"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

### Paso 3 — Activa GitHub Pages
1. En tu repositorio, ve a **Settings** (⚙️)
2. En el menú lateral, haz clic en **Pages**
3. En **Source**, selecciona **Deploy from a branch**
4. Elige la rama **main** y la carpeta **/ (root)**
5. Haz clic en **Save**

### Paso 4 — ¡Listo!
Después de 1-2 minutos, tu página estará en:
```
https://TU_USUARIO.github.io/TU_REPO/
```

---

## Funcionalidades incluidas

- 🏆 **Torneos** — Crea torneos de MK, Valorant y Street Fighter con premios, fechas y slots
- 🎯 **Brackets** — Sistema visual de eliminación con cuartos, semis y final
- 👥 **Equipos** — Crea equipos con logo emoji, tag y miembros
- 👤 **Perfil** — Cambia tu nombre, handle, bio, avatar (emoji o foto)
- 🔍 **Filtros** — Filtra torneos por juego o estado
- 📊 **Historial** — Registro de participaciones y premios

---

## Estructura de archivos

```
tu-repositorio/
└── index.html   ← todo en un solo archivo
```

Un solo archivo = cero dependencias, cero instalaciones, funciona en cualquier hosting.
