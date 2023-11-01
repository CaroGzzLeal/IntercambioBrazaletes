# IntercambioBrazaletes

El intercambio de brazaletes es una actvidad que se ha vuelto muy popular en los últimos meses en conciertos. Consiste en realizar brazaletes con temáticas relacionadas al cantante, ya sea las iniciales de alguna de sus canciones o una frase icónica de esa persona. Los fans van a los conciertos con estos brazaletes y los intercambian entre si, ya sea por diseños que les gusten más, para conseguir alguno en específico, o solo por diversión.
En una sala de cine se va a transmitir un concierto. Los fans están muy emocionados por poder llevar a cabo esta dinámica en la sala de cine, no obstante al ser un cine esta actividad se llevará a cabo de una manera más controlada, con el fin de brindar una maravillosa experiencia a todos los que asistan, que se puedan intercambiar los brazaletes, además de que puedan disfrutar la película y pasar un buen rato. 
Esta es una simulación que muestra esta actividad basada desde El Juego de la Vida del matemático John Horton Conway. 

<center>
<img src="https://i.etsystatic.com/22925573/r/il/1a0dd2/4899550808/il_fullxfull.4899550808_387n.jpg" width=250 height=300 />
</center>

# Reglas

El entorno en donde se realiza esta actividad, cuadrícula ortogonal bidimensional de celdas cuadradas, cada una de ellas se encuentra en alguno de los 3 posibles estados: Regalando brazaletes, pidiendo brazaletes, o disfrutando la película.
Cada celda interactúa con ocho vecinos, que son las celdas adyacentes horizontales, verticales y diagonales. En cada paso de tiempo, las siguientes transiciones ocurren:

1. Las personas(celdas) llegan a la sala de cine con entre 0 y 20 pulseras. 
2. Las personas con menos de 10 brazaletes (0 - 9) pueden pedir a otra persona que les regale una. 
3. Las personas con más de 10 brazaletes (11 - 20) pueden regalar brazaletes a otra persona.
4. Las personas que tienen 10 pulseras exactamente se sientan a disfrutar la película, ya no intercambian brazaletes.

<center>
<img src="[Animacion](https://github.com/CaroGzzLeal/IntercambioBrazaletes/assets/89434246/b41ebd2b-e2ba-41e9-b9ea-a687fc5e70eb)" width=250 height=300 />
</center>
