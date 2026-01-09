# Salta y evita la Torre Eiffel 🗼

Mini juego en una sola página (HTML/CSS/JS) listo para **GitHub Pages**.

## Cómo publicarlo en GitHub Pages (rápido)
1. Crea un repo en GitHub (por ejemplo: `eiffel-jump-game`).
2. Sube **estos archivos tal cual** (asegúrate de que `index.html` quede en la raíz del repo, al mismo nivel que la carpeta `assets/`).
3. En GitHub: **Settings → Pages → Build and deployment**
   - Source: *Deploy from a branch*
   - Branch: `main` / *(root)*
4. Guarda y abre la URL que te aparece.

## Personalización
- Sprite (cara): `assets/face_sprite.png`
- Objetivo (10): busca `const GOAL = 10;` en `index.html`.
- Texto del vale: en el bloque del overlay del vale, dentro de `#voucher`.

### Dificultad (progresiva pero fácil)
En `index.html`, ajusta el objeto `DIFF` para tocar velocidad, altura de torres y tiempo entre torres.
