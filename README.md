# Generador de árboles

Aplicación web (un solo `index.html`, sin dependencias) que dibuja árboles fractales con el mismo
método recursivo original: cada rama genera dos o tres ramas hijas cuyo ángulo es
`apertura / (1.5 + azar·2.5)` y cuya longitud es `longitud / (1.2 + azar)`.

## Funciones
- **Semilla reproducible**: la misma semilla y los mismos ajustes producen siempre el mismo árbol.
- **Estilos predefinidos**: Clásico (idéntico al original), Roble, Cerezo, Otoño, Sauce, Invierno, Neón.
- **Controles**: profundidad, ramas por nodo, apertura, azar en ángulos y longitudes, viento, poda,
  grosor y adelgazamiento de ramas, hojas y colores.
- **Animación de crecimiento** por niveles.
- **Ajuste automático** del árbol al tamaño de la pantalla (también en móvil) y nitidez en pantallas HiDPI.
- **Exportar PNG** en alta resolución (con fondo transparente opcional) y **copiar enlace** para compartir un árbol.
- Atajo: **Espacio** o **Enter** genera un árbol nuevo.

Abre `index.html` en el navegador para usarla.
