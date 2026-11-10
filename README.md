# Backtracking Challenge - Ndamas - Vibethon EAFIT 2026

Programa de juego interactivo creado en HTML mediante vibecoding, para el reto-warmup de la Vibethon EAFIT 2026.

# Dinámica y juego

- **Descripción:**

El algoritmo del backtracking aplicado al problema de las n-damas nos ayuda a calcular todas las posiciones donde es posible colocar n damas en un tablero cuadrado de tamaño n x n, evitando colisiones horizontales, verticales y diagonales.

- **Juego:**

a) El usuario registra e inicia una partida ingresando su nombre, esta se guarda en la memoria local del dispositivo. 

b) La partida consta de 3 niveles, donde en cada uno el reto es ubicar 4, 5 y 6 damas en un tablero de tamaño 4x4, 5x5 y 6x6 respectivamente, se inicia el primer nivel y solo se puede pasar al próximo si el anterior se completó. 

c) Al comenzar una partida, un cronómetro empieza a contar y se detiene solo durante la transición de un nivel a otro, o si se finalizó/perdió la partida.

d) Solo hay 3 vidas durante toda la partida, no se reinician, sino que se acumulan. Si se ubica una dama en una casilla donde hay colisión, se pierde una vida que no se puede recuperar hasta iniciar otra partida.

e) La partida finaliza si y sólo si: se pierden las 3 vidas sin completar los 3 niveles, o se completan los 3 niveles. 

- **Puntaje y clasificación:**

Completar cada partida da 100 puntos, siendo así, el puntaje mínimo 0 puntos, y el máximo posible 300. Al finalizar una partida, esta se guarda en un ranking (también guardado en la memoria del dispositivo), con todas las partidas registradas, el puntaje de cada una, y el tiempo guardado por el cronómetro.

En caso de empate de puntos, el criterio de desempate es el tiempo, donde gana el jugador con el menor tiempo registrado. Si dos o más jugadores empatan tanto en puntos, como en tiempo, el puesto dentro del ranking es compartido.

# Agradecimientos
A todo el equipo logístico y organizacional detrás del evento(feria Next, Vibethon), al equipo de jurados, y al profesor Alexander Narváez. Por la oportunidad para participar y asistir a cada uno de los eventos, charlas y competencias planificadas dentro del campus universitario.
