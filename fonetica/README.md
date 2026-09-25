# Fonética del Inglés Americano 🇺🇸

Una web para que **hispanohablantes** aprendan y practiquen todos los sonidos del **Alfabeto Fonético Internacional (AFI / IPA)** que se usan en el inglés americano (General American).

👉 **Úsala aquí:** https://andressantage.github.io/generador-arboles/fonetica/

## Qué incluye

- **🧭 Ruta de estudio:** 14 lecciones ordenadas de lo fácil a lo difícil (sheep vs. ship, las cuatro «a», B vs. V, TH, la r americana…). Cada lección tiene una práctica, y para completarla hay que sacar 8/10.
- **🔤 Tabla AFI interactiva:** 46 fonemas (12 vocales, 5 diptongos, 6 vocales con R y 24 consonantes), con colores según su dificultad para un hispanohablante.
- **Ficha de cada sonido:** cómo se pronuncia, comparación con el español, el error típico, cómo se escribe, 6 ejemplos con audio normal 🔊 y lento 🐢, y pares mínimos.
- **👄 Trapecio vocálico** con las vocales del español superpuestas y los diptongos dibujados como flechas.
- **🦷 Tabla de consonantes** por punto y modo de articulación, con las parejas sorda/sonora.
- **🇺🇸 Acento americano:** flap T, T glotal, aspiración, L oscura, terminaciones -ed y -s, formas débiles, acento de palabra, letras mudas…
- **🎮 Práctica:** pares mínimos, «¿qué sonido es?», escuchar y transcribir, leer el AFI, un modo mezcla y un repaso de tus errores.
- **🔎 Diccionario fonético:** busca palabras o toca un símbolo para ver todas las palabras que lo contienen.
- **📈 Progreso:** se guarda en tu navegador con `localStorage` e incluye racha, precisión y un mapa de sonidos.

El audio usa la **Web Speech API**, es decir, la voz en inglés de tu dispositivo. Funciona en PC y en celular.

## Archivos

| Archivo | Contenido |
|---|---|
| `index.html` | Estructura de la página |
| `estilo.css` | Estilos (tema claro/oscuro, adaptable a celular) |
| `datos.js` | Fonemas, explicaciones, ejemplos y palabras |
| `app.js` | Lógica: vistas, audio, juegos, diccionario y progreso |

Es un sitio estático, sin dependencias. Para usarlo en tu computadora, abre `index.html` en el navegador.
