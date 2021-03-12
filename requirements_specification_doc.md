# ANKAKH
ANKAKH = independiente en armenio

# Table of content

- [Introduction](#introduction)
    - [Purpose](#purpose)
    - [Scope](#scope)
    - [Definitions and Acronyms](#definitions-and-acronyms)
- [Overall Description](#overall-description)
    - [User classes](#user-classes)
    - [Assumptions and Dependencies](#assumptions-and-dependencies)
- [System Features and Requirements](#system-features-and-requirements)
    - [Functional Requirements](#functional-requirements)
    - [External Interface Requirements](#external-interface-requirements)
    - [Non-functional Requirements](#non-functional-requirements)
- [Screens](#screens)
    - [Wireframes](#wireframes)

_Table of content generated using VSCode plugin [Markdown TOC](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc)_

# Introduction
Ankakh espera ser un videojuego incluyente para niñas y niños entre las edades de 9-19 años para romper los prejuicios de la dificultad de las carreras STEAM y las mujeres en la ciencia.
Al mostrar la vida de l@s científicos e ingenieros (trabajo y vida social) esperamos cambiar el prejuicio negativo de la sociedad sobre estas carreras.

## Purpose
El proposito de nuestro juego es romper el "cliche" en el cual se cree que l@s mujeres/hombres no pueden llevar una vida social y una vida laboril exitosa. Demostrar que es posible no tener que elegir entre una de ellas.

## Scope
Ankakh un juego de toma de decisiones, en el que cual el personaje principal es manipulado por el usuario. Este podrá elegir desde la apariencia del personaje hasta las decisiones que tiene que hacer durante el día a día.  

## Definitions and Acronyms
- STEAM/STEM= Es una asociación sin fines de lucro que busca promover la enseñanza de la ciencia, ingeniería, tecnología, matemáticas y arte en los jovenes

- Carreras STEAM= ingeniería, ciencias, matemáticas, tecnología y arte

- Cliche= estereotipo

- Agenda 2030= la ONU crea la Agenda 2030 como un plan a favor de las personas y el planeta

# Overall Description
El objetivo de Ankakh es enseñar la vida en un día de l@s ingenieros y científicos de alguna carrera STEAM, enseñando que estas personas son humanos y tienen una vida normal tanto en el trabajo y como en la parte social. A largo plazo nos gustaría lograr que el personaje viaje a todo el mundo y en cada país tenga una carrera diferente (dentro de las carreras STEAM) para que el usuario pueda experimentar la diversión de cada una de ellas.
Queremos también atraer a las niñas con algo que estén familiarizadas y los juegos de este tipo son muy populares. Nos basamos pensando en juegos como "Episode" que son libros y en cada libro tienes una vida diferente con tu personaje, sin embargo estos juegos son solo de relaciones de noviazgo y nada más.

## User classes
Este juego esta enfocado en niñas de 9-19 años, con el fin de impulsarlas a estudiar carreras STEAM (ciencias, ingeniería, matemáticas, tecnología y arte). No hay una clase en espeficífico, por lo tanto se busca llegar a la mayor cantidad de niñas y niños posibles. 
Es importante recordar que es esencial tener un navegador actualizado. 

## Assumptions and Dependencies

- Dependemos que las graficas utilizadas para crear el video juego se encuentren en la Unity Store o en OpenGameArt.org.

- Dependemos en que la organizacion STEAM no cambie los requisitos ya establecidos.

- El proyecto tomara alrededor de 10 semanas para completar.

- Dependemos que la organizacion STEAM colabore con nosotros en la creacion del proyecto.

- Dependemos que con los conocimientos adquiridos en la clase podemos llegar MVP (Minimum Viable Product).

- Dependemos en Unity para la creacion del juego.

# System Features and Requirements
- El rango de edad es de 9-19 años
- Debe ser un juego inclusivo
- Debe buscar relacionarse con un objetivo de la Agenda 2030
- Fomentar carreras STEAM 

## Functional Requirements

En esta tabla describimos posibles historias o pensamientos de nuestros usuarios que podrían tener al usar el juego en su vida cotidiana.

|Título|Historia de usuario|Importancia|Notas|
|---|---|---|---|
|1|Como una mujer, me gustaría que el juego llame mi atención|para creer que yo también puedo meterme a estas carreras.|De esta manera rompemos el prejuicio de las niñas en la ciencia.|
|2|Como hombre, me gustaría que el juego también incluya mis gustos|para poder también jugarlo sin el prejuicio que es "solo para niñas".|Creamos en los niños pensamientos inclusivos.|
|3|Como niñ@, me gustaría poder entender el juego|para que pueda jugarlo en ese momento y no tener que esperar a crecer.|El juego tendrá un amplio espectro y será posible para todos jugarlo.|
|4|Como adolescente, me gustaría que no sienta que el juego|está enfocado solo a niños pequeños y mi edad no encaja.|El juego tendrá un amplio espectro y será posible para todos jugarlo.|

## External Interface Requirements
En un futuro nos gustaria crear una conexión entre los usuarios, que puedan interactuar dentro del juego.

There are several types of interfaces you may have requirements for, including:
- User -> la plataforma debe ser visualmente atractiva y fácil de usar ya que estadiseñada para jovenes
- Hardware -> en el juego se toman decisiones, por lo tanto es necesario un "mouse" para deslizarse por el juego y seleccionar la decisión elegida. Queremos agregarlse música, por o tanto el dispositivo debe contar con unas bocinas, al ser personaliazado el usuario elige el nombre del personaje de moso que un teclado es esencial, y por último una pantalla en la que se proyecte el juego.
- Software -> html, c-sharp, udemy, visualStudio, gitHub, Wndows y Mac

## Non-functional Requirements

 - El Video Juego se creara utilizando Unity.
 - El Video Juego debera de promover las carreras STEAM.
 - El Video Juego se debe accesar por medio de una pagina web.
 - El Game Loop estara representado por un dia comun en la vida de un ingenier@.
 - La programacion se hara en C#.


# Screens

- Menú Principal

    El menú principal será la primera escena en aparecer, ésta contendrá un menú que contendrá 3 opciones: Jugar, Opciones y Salir.La opción de jugar nos llevará a la escena 'Character Menu'. La opción de opciones nos llevará a la escena 'Options Menu'. La opción de salir nos sacará del juego.

- Options Menu

    Dentro de esta escena podremos ajustar el volumen de la música del juego. Esto se realizara por medio de un slider interactivo que representará el volumen actual de la música del juego. También habrá una opción 'Back' la cual nos regresará a la escena 'Main Menu'.

- Character Menu

    En esta escena podrá elegir el contexto (carrera elegida) en el cual el juego se desarollará. Esto se hará con una lista horizontal de opciones (éstas siendo las diferentes carreras STEAM disponibles). Esta sección estará denominada 'Carrera'. Al igual existirá otra sección con varias listas horizontales de opciones que servirán para elegir el atuendo del personaje. A esta sección estará denominada 'Personaje'. Por último existirán dos botones con las opciones de 'Empezar' y 'Regresar'. Al oprimir el botón de 'Regresar' la escena regresará al menu principal (escena 'Main Menu'). Por el otro lado, al oprimir el botón de 'Empezar' la escena cambiará a 'Decisión 1',y comenzará el juego.

- Decisión 1

    De esta escena hasta la escena 'End Game' es considerada como el juego principal. Dicho esto el contexto de este cambiará de acuerdo a la carrera que haya elegido el jugador. Dentro de las escenas denominadas 'Decisión X' se encontraran con un cuadro de diálogos el cual concluirá con dos posibles opciones, las cuales dependiendo de la elegida añadirán o quitaran puntos de un sistema de puntaje escondido el cual decidirá la escena final.

- Decisión 2

    Dentro de esta escena estará propuesta la opción de continuar a las escenas denominadas 'Minigame X' o saltar a la escena 'Decisión 4'.

- Minigame Scene

    Dentro de esta escena se explicará cómo funciona el minijuego por medio de cajas de diálogo.

- Minigame

    En esta escena se jugará el minijuego.

- Minigame Post-Scene

    Dentro de esta escena se mostrara el desempeño obtenido dentro del minijuego y se otorgara la recompensa apropiada.

- Decision 3
    
    Dentro de esta escena se tendrá la opción de continuar a la escena 'Decisión 4' o saltar a la escena 'End Game'.

- Decisión 4

    Dentro de esta escena se tendrá la opción de continuar a la escena 'End Game'.
    
- End Game
    
    Dentro de ésta se mostrará el final dependiendo del puntaje obtenido durante el juego. Existen cuatro posibles finales por cada contexto. Dichos finales reflejan el balance entre trabajo y la vida social que se demostró durante el juego. Si el día se completa de manera buena, el usuario ganará monedas.

- Credits

    En esta escena se mostrarán los nombres de las personas que crearon la escena. Al terminar esta escena volveremos a la escena 'Main Menu'.

## Wireframes
Un wireframe nos ayuda a visualizar el tamaño y el acomodo de todos los elementos que habrá en la pantalla del juego, así mismo nos permite visualizar un poco mejor cómo se verá en realidad nuestro juego.

<img width="721" alt="pag1" src="https://user-images.githubusercontent.com/57368415/110400427-3bd35c80-803d-11eb-9d93-54491707d765.png">

<img width="720" alt="pag2" src="https://user-images.githubusercontent.com/57368415/110400393-2cecaa00-803d-11eb-9e46-088a21845cc7.png">

<img width="700" alt="pag3" src="https://user-images.githubusercontent.com/57368415/110400444-4130a700-803d-11eb-89d8-114ad2cf29a4.png">

<img width="718" alt="pag4" src="https://user-images.githubusercontent.com/57368415/110400451-44c42e00-803d-11eb-817f-3f8929cf3987.png">

<img width="718" alt="pag5" src="https://user-images.githubusercontent.com/57368415/110400458-47bf1e80-803d-11eb-9410-708aecdce4f9.png">

<img width="720" alt="pag6" src="https://user-images.githubusercontent.com/57368415/110400462-4aba0f00-803d-11eb-9f18-e87590d41d89.png">

<img width="721" alt="pag7" src="https://user-images.githubusercontent.com/57368415/110400470-4d1c6900-803d-11eb-9245-28487708da29.png">
