# Comprobaciones visibles de M2

Comprueba cada método antes de continuar con el siguiente:

- nivel válido y nivel inexistente;
    .El programa abre el archivo, lee las filas y las guarda en una lista para después crear los bloques
    .Antes de leer el archivo, comprueba que existe y, si no lo encuentra, muestra un error indicando que no se encuentra

- nivel con filas de distinta longitud;
    Comprueba que todas las filas tengan el mismo número de caracteres y, si alguna es diferente, muestra un error

- paleta en ambos límites de la pantalla;
    .Cuando muevo la paleta hacia la izquierda, comprueba que no salga de la pantalla y la mantiene en el borde
    .Hace lo mismo por la derecha, evitando que la paleta sobrepase el límite de la ventana

- rebote contra pared, paleta y cada tipo de bloque;
    .Cuando la bola toca una pared lateral, cambia su dirección horizontal, y cuando toca el techo, cambia su dirección vertical
    .Cuando la bola choca con la paleta mientras está bajando, rebota y vuelve hacia arriba
    .Cuando la bola toca un bloque, este desaparece, se suman los puntos correspondientes a su tipo y la bola rebota

- pérdida de una vida y reinicio de la bola;
    .Cuando la bola cae por debajo de la pantalla, se resta una vida y, si todavía quedan vidas, vuelve a colocarse encima de la paleta

- victoria al eliminar el último bloque y derrota al agotar vidas;
    .Cuando se eliminan todos los bloques, el juego detecta que no queda ninguno y muestra el mensaje de victoria
    .Cuando se pierden las tres vidas, el juego termina y muestra el mensaje de GAME OVER

- salida limpia con Escape y al cerrar la ventana.
    .Al pulsar Escape, el programa deja de ejecutar el juego y cierra Pygame

Una mejora opcional no debe romper ninguno de estos casos.
