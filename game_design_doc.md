# Ankakh
> Game Design Document

# Table of Content

- [Game Design](#game-design)
    - [Summary](#summary)
    - [Gameplay](#gameplay)
    - [Mindset](#mindset)
- [Technical](#technical)
    - [Screens](#screens)
    - [Controls](#controls)
    - [Mechanics](#mechanics)
- [Level Design](#level-design)
    - [Themes](#themes)
    - [Game Flow](#game-flow)
- [Development](#development)
    - [Abstract Classes / Components](#abstract-classes--components)
    - [Derived Classes / Component Compositions](#derived-classes--component-compositions)
- [Graphics](#graphics)
    - [Style Attributes](#style-attributes)
    - [Graphics Needed](#graphics-needed)
- [Sounds/Music](#soundsmusic)
    - [Style Attributes](#style-attributes-1)
    - [Sounds Needed](#sounds-needed)
    - [Music Needed](#music-needed)
- [Schedule](#schedule)



# Game Design

## Summary
Demostrar que una persona, especialmente las mujeres, pueden llevar tanto una vida profesional exitosa como una vida social, en las carreras STEAM. Derrumbar el “cliché” sobre las mujeres en estas carreras y mostrarle a los usuarios que pueden lograr los retos de trabajar en estas profesiones.

## Gameplay
El objetivo del juego es que el usuario tome decisiones sobre la vida del personaje, este llevará una vida social y una vida profesional en una carrera STEAM y podrán divertirse en lugares científicos, por ejemplo un laboratorio. 
	La misión del usuario será completar un día de trabajo en el que tendrá que cumplir el reto dado al final del día, dependerá de su puntuación en los minijuegos presentados a lo largo de ese “día” el resultado final del reto presentado. Ejemplo: 
Ingeniería civil: el reto dado será construir un edificio, dependerá de las decisiones del usuario si el edificio es completado con éxito o se derrumba.
	Los obstáculos del juego se dividen en dos, los presentados en el minijuego y “tentaciones” que recibirá el personaje, por ejemplo ir a comer, etc. 
	Los minijuegos tendrán que ser completados para ganar monedas y decidir el resultado final. Cada laboratorio dependerá de la carrera escogida y cada carrera estará en un país determinado al que se podrá viajar cuando el usuario tenga las suficientes monedas para desbloquearlo.
	Al principio del juego el usuario escogerá el género, carrera y “look” del avatar que usará en el juego, conforme el juego avance con las monedas ganadas a través del juego podrá ampliar la selección de “estilos”. 


## Mindset
Los sentimientos que queremos provocar con este juego son los de empoderamiento, ya que buscamos que el usuario se dé cuenta que puedes tener “lo mejor de dos mundos”.  
	Los usuarios podrán identificarse con el sentimiento de su avatar al final del día y esa será su motivación para completar cada reto de la mejor manera posible, la satisfacción que tendrán con cada reto completado con éxito los animará a saber que lo pueden lograr y querrán probar escenarios en otras carreras.
Se quiere dar el mensaje de que puede haber un balance en todo y lograr que los usuarios lo experimenten con su propio avatar.


# Technical
 
## Screens


1.Casa
   a. Elegir vestuario
2.Laboratorio
   b. Hay un minijuego de las carreras STEAM
3.Restaurante
   c. Aquí se verá el resultado del reto del día
End Credits



## Controls
Se basará en una forma de narración. El jugador va a recibir opciones de las decisiones que hará el personaje durante el juego. También podrá jugar minijuegos dentro de los diferentes escenarios que se vayan presentando alrededor del día.
	Sus decisiones determinarán el resultado final del reto del día, la oportunidad de ir subiendo de nivel en cada carrera, y viajar para probar carreras diferentes .


## Mechanics
Dependerá del nivel la dificultad en cada minijuego, los “obstáculos” de éstos serán completarlos en un tiempo determinado. Si no se alcanza el puntaje necesario no se completará el reto del día.
	Los retos semanales se darán como algo opcional para el usuario, pero si los logra se le dará una recompensa monetaria con la cual podrá alcanzar nuevos niveles.
	Tendremos 3 escenarios como base para todas las carreras: casa, laboratorio, lugar social (ejemplo: restaurante). Esos escenarios se irán adaptando de una manera sencilla de acuerdo a los artículos necesarios para cada carrera y para que el usuario se sienta en otro mundo.
	Cada animación entre los escenarios será un video corto que el usuario no podrá controlar y que solo enseñará como el avatar llega de un lugar a otro.
	Las decisiones que tomará el personaje serán a) ó b) y con eso podremos determinar el final de su día. Habrá 4 posibles finales basándonos en cuántas decisiones a) y b) tomó el usuario.


# Level Design


## Themes

1. Casa

	a. Mood
		    
    -  Ambiente moderno, paz, cuarto de ensueño
		
		
	b. Objetos

	- Ambiente
		
		1. Cama, closet, escritorio, espejo,baño

		2. Luz de amanecer
			
		3. Colores neutros

	- Interactive
		
		1. Computadora
			 
		2. Espejo
			 
		3. Cama
2. Laboratorio


	a. Mood
	
	- Grande, blanco
		
	b. Objetos
	
	- Ambient
		
		1. Químicos
		2. Mecheros, regadera de emergencia, pipetas, fregadero
		3. Tabla periódica
			
	- Interactive
		
		1. Estaciones para diferentes experimentos
		2. Vestuario para adentro del laboratorio
		3. Compañeros de trabajo




## Game Flow

1.	El jugador elige la carrera de su preferencia.
2.	Al despertar el jugador elige el género y ropa de su personaje.
3.	La primera decisión se tomará.
4.	La segunda decisión se tomará.
5.	Si el jugador lo elige, puede ir a trabajar a su laboratorio en donde dependiendo de la carrera que eligió podrá jugar un minijuego relacionado a dicha carrera.
6.	En el minijuego el jugador tendrá un objetivo que cumplir y dependiendo de su desempeño se le otorgara un puntuación. 
7.	Al salir del trabajo el jugador puede decidir si ir con sus amigos o ir a su casa
8.	Dependiendo la decisión la combinación de las decisiones tomadas durante el día se mostrará uno de 4 posibles finales. 


- Al despertar el jugador elige el género y ropa de su personaje.
- El jugador podrá decidir la carrera en la que quiere jugar.
- El usuario irá a su laboratorio donde encontrará el minijuego del día.
- Al completar el juego se ganarán monedas.
- Se verá el resultado del puntaje.



# Development
 
## Abstract Classes / Components

1. BasePhysics
	a. BasePlayer= el personaje principal creado por el usuario
	b. BaseEnemy= no hay
	c. BaseObject= dependiendo el minijuego
2. BaseObstacle= los retos por minijuegos y retos opcionales semanales
3. BaseInteractable= las dos opciones presentadas al usuario. En el laboratorio un objeto que al ser seleccionado despliega el juego. 



## Derived Classes / Component Compositions

1. Jugador base
	a. PlayerMain= personaje diseñado por el usuario con las opciones presentadas
	b. PlayerUnlockable= a lo largo de los minijuegos el usuario va ganando monedas con las cuales puede desbloquear más opciones de personalizado
2. Enemigo= no hay
3. Objeto Base= dependiendo el mimijuego
	a. Ingenieria Electrónica: cables, focos.


	a. PlayerMain -> Personaje diseñado por el usuario con las opciones presentadas
	b. PlayerUnlockable -> A lo largo de los minijuegos el usuario va ganando monedas con las cuales puede desbloquear más opciones de personalizado
2. BaseObject 


# Graphics

## Style Attributes
What kinds of colors will you be using? Do you have a limited palette to work with? A post-processed HSV map/image? Consistency is key for immersion.

What kind of graphic style are you going for? Cartoony? Pixel-y? Cute? How, specifically? Solid, thick outlines with flat hues? Non-black outlines with limited tints/shades? Emphasize smooth curvatures over sharp angles? Describe a set of general rules depicting your style here.

Well-designed feedback, both good (e.g. leveling up) and bad (e.g. being hit), are great for teaching the player how to play through trial and error, instead of scripting a lengthy tutorial. What kind of visual feedback are you going to use to let the player know they’re interacting with something? That they *can* interact with something?

## Graphics Needed

1.	Characters
    a.	Human-like
        i.	Goblin (idle, walking, throwing)
        ii.	Guard (idle, walking, stabbing)
        iii.	Prisoner (walking, running)
    b.	Other
        i.	Wolf (idle, walking, running)
        ii.	Giant Rat (idle, scurrying)
2.	Blocks
    a.	Dirt
    b.	Dirt/Grass
    c.	Stone Block
    d.	Stone Bricks
    e.	Tiled Floor
    f.	Weathered Stone Block
    g.	Weathered Stone Bricks
3.	Ambient
    a.	Tall Grass
    b.	Rodent (idle, scurrying)
    c.	Torch
    d.	Armored Suit
    e.	Chains (matching Weathered Stone Bricks)
    f.	Blood stains (matching Weathered Stone Bricks)
4.	Other
    a.	Chest
    b.	Door (matching Stone Bricks)
    c.	Gate
    d.	Button (matching Weathered Stone Bricks)

_(example)_

_(Note : If you’re soloing you might not need to define this part, as you can just use the Derived_ 
_Classes + Themes section as a reference. It’s up to you.)_

# Ilustraciones

## Personajes
![opcion1](https://user-images.githubusercontent.com/57368237/110866266-81389980-828a-11eb-9563-5459484d3ccb.png)
![opcion2](https://user-images.githubusercontent.com/57368237/110866278-84cc2080-828a-11eb-9ab1-31fee75278de.png)


## Ambientes
![1](https://user-images.githubusercontent.com/57368415/110865832-d922d080-8289-11eb-9fae-5e396d941b5f.jpeg)

![2](https://user-images.githubusercontent.com/57368415/110865984-14bd9a80-828a-11eb-9423-c1f58c1562c3.jpeg)

![3](https://user-images.githubusercontent.com/57368415/110865990-18512180-828a-11eb-8356-7d20aca76e83.jpeg)

![4](https://user-images.githubusercontent.com/57368415/110866001-1b4c1200-828a-11eb-9959-bf270970efd3.jpeg)

![5](https://user-images.githubusercontent.com/57368415/110866007-1dae6c00-828a-11eb-9aa6-0ccca5a06014.jpeg)




# Sounds/Music
 
## Style Attributes
Again, consistency is key. Define that consistency here. What kind of instruments do you want to use in your music? Any particular tempo, key? Influences, genre? Mood?

Stylistically, what kind of sound effects are you looking for? Do you want to exaggerate actions with lengthy, cartoony sounds (e.g. mario’s jump), or use just enough to let the player know something happened (e.g. mega man’s landing)? Going for realism? You can use the music style as a bit of a reference too.
	
Remember, auditory feedback should stand out from the music and other sound effects so the player hears it well. Volume, panning, and frequency/pitch are all important aspects to consider in both music and sounds - so plan accordingly!

## Sounds Needed

1.	Effects
    a.	Soft Footsteps (dirt floor)
    b.	Sharper Footsteps (stone floor)
    c.	Soft Landing (low vertical velocity)
    d.	Hard Landing (high vertical velocity)
    e.	Glass Breaking
    f.	Chest Opening
    g.	Door Opening
2.	Feedback
    a.	Relieved “Ahhhh!” (health)
    b.	Shocked “Ooomph!” (attacked)
    c.	Happy chime (extra life)
    d.	Sad chime (died)

_(example)_

## Music Needed

1.	Slow-paced, nerve-racking “forest” track
2.	Exciting “castle” track
3.	Creepy, slow “dungeon” track
4.	Happy ending credits track
5.	Rick Astley’s hit #1 single “Never Gonna Give You Up”
 
_(example)_

_(Note : Again, if you’re soloing you might be able to / want to skip this section. It’s up to you.)_

# Schedule
 
(what is a schedule, i don’t even. list is good enough, right? if not add some dates i guess)


1.	develop base classes
    a.	base entity
        i.	base player
        ii.	base enemy
        iii.	base block
    b.	base app state
        i.	game world
        ii.	menu world
2.	develop player and basic block classes
    a.	physics / collisions
3.	find some smooth controls/physics
4.	develop other derived classes
    a.	blocks
        i.	moving
        ii.	falling
        iii. breaking
        iv.	cloud
    b.	enemies
        i. soldier
        ii.	rat
        iii. etc.
5.	design levels
a.	introduce motion/jumping
b.	introduce throwing
c.	mind the pacing, let the player play between lessons
6.	design sounds
7.	design music


