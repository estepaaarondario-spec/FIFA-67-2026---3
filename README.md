# FIFA 67

Juego de fútbol 6 contra 6 en 3D que corre en el navegador con [Three.js](https://threejs.org). Todo está en un único `index.html`, sin compilación. Se juega solo contra la IA o de a dos en el mismo teclado.

**Equipos:** BOCA (azul y amarillo) vs RIVER (blanco y rojo).

## Controles

| | Jugador 1 (Boca) | Jugador 2 (River) |
|---|---|---|
| Mover | WASD | Flechas |
| Sprint | Shift izquierdo | Shift derecho |
| Patada (mantené y soltá) | Espacio | Enter |
| Pase | F | / |
| Picar (vaselina) | G | . |

En modo 1 jugador también podés mover con las flechas. El control salta solo al jugador más cercano al balón. Enter reinicia al terminar el partido (2:30).

## Reglas

- **Árbitro** (gordo) que sigue la jugada, pita y señala con el brazo.
- **Lateral, córner y saque de arco** según quién tocó último el balón.
- **Offside** cuando recibe un compañero que estaba adelantado al momento del pase.
- **Faltas** por entradas fuertes: tiro libre (con barrera a 9 m) o **penal** si es dentro del área. A veces hay tarjeta amarilla.
- En los saques el jugador que ejecuta usa patada, pase o picar. En el penal, apuntás con las direcciones.

## Público

La mitad izquierda de las tribunas es de Boca y la derecha de River. Festejan cuando gana su equipo; los hinchas del que pierde se ponen violentos (se les enrojece la cara, se sacuden y tiran objetos a la cancha).

## Publicar en GitHub Pages

1. Subí `index.html` y este `README.md` a un repositorio.
2. En **Settings → Pages** elegí la rama `main` y la carpeta `/ (root)`.
3. Abrí `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Necesita conexión para cargar Three.js y las fuentes desde CDN.

Proyecto de fans, no oficial. No está afiliado a FIFA, EA Sports, Boca Juniors ni River Plate; solo usa los colores y nombres como referencia.
