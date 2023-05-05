1.1
Piedra papel tijera esta hecho con el fin de mostrar avances sobre el proyecto dentro del curso
de programacion de desarrollo web de Platzi.

//<Datos que contiene el archivo>
	el archivo tiene un  DOCTIPE para el uso en ordenadores viejos.
	tiene charset "utf-8" para el teclado en español.
	su Script de la PC es una funcion donde aleatoriza con parametros
	de un minimo y un maximo.
	donde corre un retorno unsabdo funciones matematicas.
	(Math.floor) = Deja el numero entero y quita las decimales.
	(Math.random) = Muestra un número aleatorio con decimales incluidas.

Pongo al jugador como (0) ya que tiene que llenar la barra de texto.
Pongo a la PC con la funcion aleatorio donde tiene que elegir 1, 2 o 3.

otros parametros agregados son "if" | "else if" | "else".
puse a if = 1 resultaria como elección de piedra.
puse a else if = 2 en caso de no seleccionar 1 y seleccionar 2, elegiria papel.
puse a else if = 3 en caso de no seleccionar 1 ni 2 seria 3, elegiria tijera.
puse else = 0 enscaso de que no se seleccionara ninguna de las otras opciones
que salga la aleta de "elegiste ser un pendejo ajsajsjas".

todas estas seria alertas dentro de las mismas funciones

if(jugador == 1) {
|	alert("elegiste Piedra")
}

tambien puse que en caso de que las elecciones sean las misma seria un 
	if(pc=jugador) {
	|	alert("EMPATE :0")
	}
otras funciones donde si el jugador elige 1 y la pc elige 3, el jugador gana
si el jugador elige 2 y y la pc 1, el jugador gana
si el jugador elige 3 y la pc 2, el jugador gana
y tambien la funsion else encaso de no ser ninguna de estas opciones, el jugador pierde

1.2

//<Update de datos sobre el archivo>

aqui se agregan funciones donde quito las alertas de eleccion y solo lo cambi a un codigo de eleccion

se agregó la función de eleccion donde simplifica las linas de cogido de jugador y pc.

donde el if es jugada en vez de jugador o pc

para esto se cambian alertas donde ya solo muestra los resultados de eleccion de pc, elección del jugador y el resultado del juego