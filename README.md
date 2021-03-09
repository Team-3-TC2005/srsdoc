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
Ankakh espera ser un videojuego incluyente para niñas y niños entre las edades de 9-19 años para romper los prejuicios de la dificultad de las carreras STEM y las mujeres en la ciencia.
Al mostrar la vida de l@s científicos e ingenieros (trabajo y vida social) esperamos cambiar el prejuicio negativo de la sociedad sobre estas carreras.

## Purpose
El proposito de nuestro juego es romper el "cliche" en el cual se cree que l@s mujeres/hombres no pueden llevar una vida social y una vida laboril exitosa. Demostrar que es posible no tener que elegir entre una de ellas.

## Scope
Ankakh un juego de toma de decisiones, en el que cual el personaje principal es manipulado por el usuario. Este podrá elegir desde la apariencia del personaje hasta las decisiones que tiene que hacer durante el día a día.  
Describe the software being specified. Include benefits, objectives, and goals. This should relate to overall business goals, especially if teams outside of development will have access to the SRS

## Definitions and Acronyms
Include any non-trivial definition or acronym used in the document.

# Overall Description
El objetivo de Ankakh es enseñar la vida en un día de l@s ingenieros y científicos de alguna carrera STEAM, enseñando que estas personas son humanos y tienen una vida normal tanto en el trabajo y como en la parte social. A largo plazo nos gustaría lograr que el personaje viaje a todo el mundo y en cada país tenga una carrera diferente (dentro de las carreras STEAM) para que el usuario pueda experimentar la diversión de cada una de ellas.
Queremos también atraer a las niñas con algo que estén familiarizadas y los juegos de este tipo son muy populares. Nos basamos pensando en juegos como "Episode" que son libros y en cada libro tienes una vida diferente con tu personaje, sin embargo estos juegos son solo de relaciones de noviazgo y nada más.

## User classes
User classes and characteristics are critical. You’ll need to define who (different roles) is going to use the product and how. Don't forget to include each user needs.

## Assumptions and Dependencies

- Dependemos que las graficas utilizadas para crear el video juego se encuentren en la Unity Store o en OpenGameArt.org.

- Dependemos en que la organizacion STEAM no cambie los requisitos ya establecidos.

- El proyecto tomara alrededor de 10 semanas para completar.

- Dependemos que la organizacion STEAM colabore con nosotros en la creacion del proyecto.

- Dependemos que con los conocimientos adquiridos en la clase podemos llegar MVP (Minimum Viable Product).

- Dependemos en Unity para la creacion del juego.

# System Features and Requirements
This is where you detail the specific requirements for building your product.

## Functional Requirements
The functional requirements describe the services and functions of a system. Functional requirements must be precise and unambiguous.

En esta tabla describimos posibles historias o pensamientos de nuestros usuarios que podrían tener al usar el juego en su vida cotidiana.

|Title|User story|Importance|Notes|
|---|---|---|---|
|1|Como una mujer, me gustaría que el juego llame mi atención|para creer que yo también puedo meterme a estas carreras.|_Write here any additional consideration_|
|2|Como hombre, me gustaría que el juego también incluya mis gustos|para poder también jugarlo sin el prejuicio que es "solo para niñas".|_Write here any additional consideration_|
|3|Como niñ@, me gustaría poder entender el juego|para que pueda jugarlo en ese momento y no tener que esperar a crecer.|_Write here any additional consideration_|
|4|Como adolescente, me gustaría que no sienta que el juego|está enfocado solo a niños pequeños y mi edad no encaja.|_Write here any additional consideration_|

## External Interface Requirements
External interface requirements are types of functional requirements. They outline how your product will interface with other components or systems.

There are several types of interfaces you may have requirements for, including:
- User
- Hardware
- Software
- Communications

## Non-functional Requirements
Non-functional requirements are restrictions on the system or the development process. Non-functional requirements can be more critical than functional ones. If they are not met, the system is useless!

# Screens

- Menú Principal

    El menú principal será la primera escena en aparecer, ésta contendrá un menú que contendrá 3 opciones.

    Esta escena mostrara el título de juego al igual que tres posibles opciones. Estas opciones serán: Jugar, Opciones y Salir. La opcion de jugar nos llevara a la escena 'Character Menu'. La opcion de opciones nos llevara a la escena 'Options Menu'. La opcion de salir nos sacara del juego.

- Options Menu

    Dentro de esta escena podremos ajustar el volumen de la musica del juego. Esto se realizara por medio de un slider interactivo que representara el volumen actual de la musica del juego. Tambien habra una opcion 'Back' la cual nos regresara a la escena 'Main Menu'.

- Character Menu

    En esta escena podra eleguir el contexto en el cual el juego se desarollara. Esto se hara con una lista horizontal de opciones (estas siendo las diferentes carreras STEAM). Esta seccion estara denominada 'carrera'. Al igual existira otra seccion con varias listas horizontales de opciones que serviran para eleguir el atuendo del personaje. A esta seccion estara denominada 'personaje'. Por ultimo existiran dos botones con las opciones de 'empezar' y 'regresar'. Al oprimir el boton de 'regresar' la escena cambiara a el menu principal (escena 'Main Menu'). Por el otro lado, al oprimir el boton de 'empezar' la escena cambiara a 'Desicion 1'.

- Decision 1

    De esta escena hasta la escena 'End Game' es considerada como el juego principal. Dicho esto el contexto de este cambiara de acuerdo a la carrera que haya eleguido el jugador. Dentro de las escenas denominadas 'Decision X' se encontraran con un cuadro de dialogos el cual concluira con dos opciones, las cuales dependiendo de la eleguida añadiran o quitaran puntos de un sistema de puntaje escondido el cual decidira la escena final.

- Decision 2

    Dentro de esta escena estara propuesta la opcion de continuar a las escenas denominadas 'Minigame X' o saltar a la escena 'Decision 4'.

- Minigame Scene

    Dentro de esta escena se explicara como funciona el minijuego por medio de cajas de dialogo.

- Minigame

    En esta escena se jugara el minijuego.

- Minigame Post-Scene

    Dentro de esta escena se mostrara el desempeño obtenido dentro del minijuego y se otorgara la recompenza apropiada.

- Decision 3
    
    Dentro de esta escena se tendra la opcion de continuar a la escena 'Decision 4' o saltar a la escena 'End Game'.

- Decision 4
- End Game
    
    Dentro de esta se mostrara el final depenediendo del puntaje obtenido durante el juego. Existen cuatro posibles finales por cada contexto. Dichos finales reflejan el balance entre trabajo y la vida social que se demostro durante el juego.

- Credits

    En esta escena se mostraran los nombres de las personas que crearon la escena. Al terminar esta escena volveremos a la escena 'Main Menu'.

## Wireframes
Wireframes are simple page layouts that outline the size and placement of elements, and features on a page. They are generally devoid of color, font styles, logos or any design elements.

Wireframing is probably the most time-consuming step of this process and for some simple projects, it may be overkill. For complex projects where serious design thinking needs to happen, wireframes are an indispensable tool.

Here are some popular tools for wireframing:
- https://marvelapp.com/  
- https://balsamiq.com/ 
- https://jetstrap.com/ 
- https://www.fluidui.com/ 
- https://ninjamock.com/ 
- https://www.justinmind.com/ 
- https://moqups.com/
