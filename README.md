# Generador de árboles (y más)

Colección de generadores procedurales en el navegador, sin dependencias. Todos siguen la misma
metodología: números aleatorios con **semilla** (la misma semilla y ajustes dan siempre el mismo
resultado), parámetros ajustables, estilos predefinidos, animación de dibujo, exportación a PNG y
enlaces para compartir.

| Página | Qué genera |
| --- | --- |
| `index.html` | Árboles fractales con el método recursivo original: cada rama genera ramas hijas con ángulo `apertura / (1.5 + azar·2.5)` y longitud `longitud / (1.2 + azar)`. |
| `rostros.html` | Rostros: forma de la cara, ojos, cejas, nariz, boca, peinados, barba, gafas, pecas y colores. |
| `carros.html` | Carros vistos de lado: sedán, deportivo, SUV, pickup, furgoneta y compacto, con rines, franjas, alerón y escena de día o de noche. |
| `casas.html` | Casas: pisos, ventanas, tipos de techo, garaje, chimenea, cerca, momento del día y árboles fractales en el jardín. |
| `humanos.html` | Personas de cuerpo completo: estatura, complexión, pose, ropa y la cabeza del generador de rostros. |
| `mundo.html` | Un barrio con 9 casas, carretera, carros en movimiento, personas caminando, rostros en las ventanas y árboles fractales. Todo se aleatoriza con una semilla y se puede recorrer con un personaje (flechas o WASD, E para saludar o tocar el timbre, C para subir a tu carro). |
| `antes_arboles.html` | La versión original del generador de árboles. |

`comun.js` y `comun.css` contienen la base compartida. Cada generador vive en su propio archivo (`rostro.js`, `carro.js`, `casa.js`, `humano.js`) para poder combinarlos en el mundo.

Atajo: **Espacio** o **Enter** genera uno nuevo. Abre cualquiera de los `.html` en el navegador para usarlo.
