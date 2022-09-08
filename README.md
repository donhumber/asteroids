# Canvas-galaxy
Live demo https://donhumber.github.io/canvas-galaxy/

El siguiente proyecto recrea una galaxia aleatorea en la que constantemente ingresan asteroides, los cuales pueden colisionar con los planetas, el sol o el mouse, estos asteroides sienten la gravedad del mouse y los planetas, por lo que sus trayectorias se ven afectadas al acercarse a uno de estos objetos.


## Iniciar libreria
Para iniciar la animación se debe llamar a la funcion "Asteroids"

Asteroids(lpcanvas,lpasteroids=40,lpplanets=10,lpstars=200,lpbackground = "rgb(0,0,0)");

## Parametros
### lpcanvas
Es mandatoria, debe contener el nombre del canvas a usar
### lpasteroids
Es opcional, indica cuantos asteroides se van a visualizar en la pantalla, por defecto se visualizan 40
### lpplanets
Es opcional, indica cuantos planetas se van a visualizar en la pantalla, por defecto se visualizan 10
### lpstars
Es opcional, indica cuantas estrellas se van a visualizar en la pantalla, por defecto se visualizan 200
### lpbackground
Es opcional, indica el color del fondo, por defecto es negro
