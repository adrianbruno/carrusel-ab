# 🎞 Carrusel AB

**Creador de carruseles profesionales para Instagram.**
Dividí una foto en 2, 3 o 4 partes para el efecto panorámico, o armá un carrusel con varias fotos. Ajustá el encuadre, el zoom y el fondo desde el celular o la computadora — sin instalar nada.

🔗 [@carruselab](https://instagram.com/carruselab) en Instagram

---

## Funciones

- ✂️ **Dividir 1 foto** en 2, 3 o 4 partes iguales para carrusel panorámico
- 🖼 **Carrusel múltiple** con hasta 10 fotos, reordenables con drag & drop
- 📐 **3 formatos oficiales**: Vertical 4:5 ★, Cuadrado 1:1, Horizontal 1.91:1
- 🎯 **Editor de encuadre** con zoom, pan y ancla de posición inicial
- 🎨 **Fondo personalizado** con selector de color libre
- 📱 **Vista previa** estilo Instagram antes de descargar
- ⚡ **PWA instalable** desde el celular sin pasar por las tiendas
- 🔒 **Privacidad total** — ninguna foto sale de tu dispositivo

---

## Publicar en GitHub Pages (paso a paso)

### 1. Crear el repositorio

1. Andá a [github.com](https://github.com) e iniciá sesión
2. Hacé clic en **New repository**
3. Nombre: `carrusel-ab`
4. Dejalo **Public**
5. NO marques "Add README"
6. Hacé clic en **Create repository**

### 2. Subir los archivos

**Desde el navegador (más fácil):**

1. En el repositorio vacío, hacé clic en **uploading an existing file**
2. Arrastrá estos archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `logo.svg`
   - `README.md`
3. Mensaje: "Primera versión Carrusel AB"
4. Hacé clic en **Commit changes**

### 3. Activar GitHub Pages

1. **Settings → Pages**
2. Branch: **main** / folder: **/ (root)**
3. **Save**
4. En 1-2 minutos tu URL será: `https://TU_USUARIO.github.io/carrusel-ab`

---

## Íconos PWA

Creá una carpeta `icons/` con:
- `icons/icon-192.png` — 192×192px
- `icons/icon-512.png` — 512×512px

Generalos desde `logo.svg` en [favicon.io](https://favicon.io) o [realfavicongenerator.net](https://realfavicongenerator.net).

---

## Dominio propio

Para usar `carruselab.com` o `carruselab.app`:
1. GitHub Pages → Custom domain → escribí tu dominio
2. En tu registrador: CNAME → `TU_USUARIO.github.io`

---

## Roadmap

- [ ] Íconos PWA generados desde logo.svg
- [ ] Dominio carruselab.com / carruselab.app
- [ ] Integración Stripe (suscripción mensual)
- [ ] Publicación directa a Instagram (API)

---

Hecho con ♡ por **Adrián Bruno** · [@carruselab](https://instagram.com/carruselab)
