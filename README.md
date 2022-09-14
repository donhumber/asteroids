# Canvas-galaxy
Live demo https://garciarussi.com/canvas-galaxy/

El siguiente proyecto recrea una galaxia aleatorea en la que constantemente ingresan asteroides, los cuales pueden colisionar con los planetas, el sol o el mouse, estos asteroides sienten la gravedad del mouse y los planetas, por lo que sus trayectorias se ven afectadas al acercarse a uno de estos objetos.


## Iniciar libreria
Para iniciar la animación se debe llamar a la funcion "Asteroids"

Asteroids(lpcanvas,lpasteroids,lpplanets,lpstars,lpbackground);

## Parametros
### Canvas
Es mandatoria, debe contener el nombre del canvas a usar
### Asteroids
Es opcional, indica cuantos asteroides se van a visualizar en la pantalla, por defecto se visualizan 40
### Planets
Es opcional, indica cuantos planetas se van a visualizar en la pantalla, por defecto se visualizan 10
### Stars
Es opcional, indica cuantas estrellas se van a visualizar en la pantalla, por defecto se visualizan 200
### Background
Es opcional, indica el color del fondo, por defecto es negro
