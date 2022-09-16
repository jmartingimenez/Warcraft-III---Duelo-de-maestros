# Warcraft III - Duelo de maestros

*Duelo de maestros ofrece una selección de héroes para enfrentarse en combates 1v1. Cada uno posee una habilidad propia, una habilidad compartida por todos, y puede comprar dos habilidades junto a un objeto con alguna utilidad determinada para personalizar cada batalla. La particularidad del gameplay consiste en que no puede controlarse el movimiento de los héroes de forma directa. De forma natural ambos contendientes buscaran atacarse. **Pueden esquivarse ataques o reposicionarse usando la habilidad de teletransportación**, compartida por todos los héroes.*

![Imagen del gameplay](Images/SS_03_Pelea.png)

Este repositorio contiene las versiones desprotegidas de un proyecto de mapping realizado con la herramienta World Editor que empecé hace algunos años.

Personalmente, aprender a usar esta herramienta fue lo que me acercó al mundo de la programación. Dado que no actualizo mas este mapa, pense en dejar la versión editable pública.


## Disclaimer

Dado que esto fue creciendo cuando recién empezaba a entender programación, es probable encontrar triggers que incluso con las limitaciones que tiene el editor podrían modularizarse mejor para evitar algunas repeticiones.

Hoy en día para editar hay herramientas mas avanzandas que el editor original como [Wurst](https://wurstlang.org/).

## Uso

El repositorio contiene las versiones principales del mapa totalmente desprotegidas, por lo que pueden cargarse dentro de Warcraft III sin problemas. Dicho esto, recomiendo descargar la versión protegida y optimizada con la herramienta de Vexorian (*la cual esta incluída en este repositorio*) desde EpicWar haciendo click en este [LINK](https://www.epicwar.com/maps/294148/). 

**El mapa fue probado en las versiones 1.26 y 1.27. No puedo garantizar su funcionamiento en versiones previas o Post 1.29.**

El mapa desprotegido puede servir para alguien intentando aprender a usar el editor de mundos de Warcraft III. El mapa contiene entre varios sistemas lo siguiente...

```
* Sistema de selección de héroes en taverna
* Sistema de compra de habilidades u objetos
* Manejo de regiones
* Validación de cantidad de jugadores
* Comandos para alterar el juego
* Uso de mensajes con colores hexadecimales
* 6 slots para jugadores o IA
* Multiboard (Tabla de posiciones)
* Sistema Queue para alternar entre jugadores
* F.A.Q. detallado
* Timers para las diferentes etapas del juego
    - Compra
    - Pelea
    - Cambio de jugadores
* Habilidades custom. Incluyendo triggers, dummy units
* Triggers para debugging que se pueden habilitar
* Uso de preload para precargar recursos al inicio
* Manejo de Arrays para control de jugadores, habilidades u objetos
* Textos flotantes para ciertas ocasiones
* IA para cada héroe (Triggers que se activan/desactivan)
* IA para uso de habilidades/objetos por héroes manejados por IA
* Control de Memory Leaks
```

## Imagenes

### F.A.Q

![Imagen del gameplay](Images/SS_01_FAQ.png)

### Descripciones y mensajes  a color

![Imagen del gameplay](Images/SS_02_Descripcion_Heroe.png)

### Ejemplo de trigger para habilidad custom con uso de Dummy unit

![Imagen del editor de triggers](Images/TR_01_Habilidad_dummy.PNG)

### Ejemplo de trigger para definir mensaje a color

![Imagen del editor de triggers](Images/TR_02_Mensaje_con_colores.PNG)

### Ejemplo de trigger para la IA de un héroe

![Imagen del editor de triggers](Images/TR_03_IA_Treant.PNG)
