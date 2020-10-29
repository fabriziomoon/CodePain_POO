# Definición de Requerimientos

## Actores del sistema

- Usuario
- Página web
- Cliente
- API
- Socket
- Base de datos

## Requerimientos de usuario

El usuario puede crearse una cuenta, ingresar a su cuenta y disfrutar del juego multijugador.

## Requerimientos de sistema

En el caso del que el usuario sea un nuevo jugador, este debe ingresar a la página principal del juego para poder crearse una cuenta, seguido de ello el sistema le pide que verifique su correo electrónico, posteriormente se le añade a la base de datos y se le permite acceder a una cuenta nueva, dónde al ingresar se inicializará el tutorial que explicará el menú y lo guiará para empezar a jugar. Una vez en el juego le explicará las mecánicas y los controles, una vez terminado el tutorial se le dejará continuar libremente su estadía.

Cuando el usuario ya tiene una cuenta, el sistema le pedirá al usuario que inicie sesión, una vez terminada esa parte le dejará acceder a su cuenta. Si después desea entrar al juego, el sistema deberá dejarlo aparecer en la "zona segura".

## Requerimientos funcionales

- El usuario debe poder crearse una cuenta.
- El usuario, para poder crear una cuenta, debe confirmar que el correo electrónico que ingresó es suyo.
- El usuario debe poder iniciar sesión.
- El usuario, en caso de ser nuevo, debe pasar por el tutorial.
- El usuario puede jugar a cualquier hora del día (excepto en horarios de mantenimiento).
- El usuario puede desconectarse en cualquier momento.
- El usuario puede comunicarse e interactuar con otros usuarios.
- El usuario puede interactuar con los NPC's.
- El usuari puede consultar las normas de convivencia.
- El usuario recibirá alertas por mal comportamiento si no cumple las normas.

## Requerimientos no funcionales

- El usuario siempre, al conectarse, empieza su juego en una "zona segura".
- En caso de hostigamiento, el usuario deberá recibir una llamada de atención.
- Una vez recibida la llamada de atención, el usuario podrá ser baneado temporalmente si continua con malas actitudes.
- Tras tres baneos temporales, será baneada permanentemente la cuenta del usuario.
- En caso de baneo permanente por segunda vez consecutiva a la misma IP, se baneará permanentemente esa IP.
- La interfaz principal te muestra las distintas secciones que puedes consultar en el cliente.
- La interfaz presenta las últimas noticias del juego.
- Antes de jugar, puedes elegir el universo donde quires jugar en el mapa.
- El tutorial solo puede saltarse una vez que te haya hecho entrar al juego.
- El chat no debe tardar más de dos segundos en mandar y recibir mensajes.
- El servidor debe soportar al menos a cuarenta personas.
- El servidor debe tener implementado un sistema de seguridad contra ataques.
- Cada sección del sistema debe de contar con su debida documentación.
- El servidor debe ser capaz de reiniciarce en caso de fallos.

## Historias de usuario

* Como usuario puedo crear una cuenta.
* Como usuario puedo verificar mi cuenta.
* Como usuario puedo acceder a un menú despues de registrarme.
* Como usuario accedo a un tutorial interactivo que me explica el menú y las mecánicas del juego.
* Como usuario puedo entrar al juego, un mapa básico, donde puedo encontrarme con otros jugadores.
* Como usuario puedo atacar los NPC's.
* Como usuario puedo interactuar con ciertos NPC.
* Como usuario puedo robar recursos de naves destruidas.
* Como usuario puedo escribir en un chat.
* Como usuario puedo ver mensajes de otros usuarios que hayan esscrito en el chat.
* Como usuario tengo un límite de mejoras basado en mi nivel actual.
* Como usuario puedo explorar puedo explorar el mapa.
* Como usuario, si me quedo afk un determinado tiempo, soy desconectado del servidor por inactividad.
* Como usuario puedo reconectarme cuando desee (excepto si fui baneado) en la zona segura.
* Como usuario puedo consultar las normas de convivencia.
* Como usuario puedo ser baneado por mal comportamiento.
* Como usuario puedo consultar y comprar mejoras de estadísticas base.
* Como usuario puedo interactuar con un sistema de mercado básico.

## Diagrama casos de uso

<img src="https://raw.githubusercontent.com/JoshuaMeza/CodePain_POO/master/Recursos/DiagramaCasos.jpg" witdh=50% margin=auto>

## Diagramas UML

### Cliente

<img src="https://raw.githubusercontent.com/JoshuaMeza/CodePain_POO/master/Recursos/Client.png" witdh=40% margin=auto>

### API

<img src="https://raw.githubusercontent.com/JoshuaMeza/CodePain_POO/master/Recursos/Api.jpg" witdh=30% margin=auto>

### Base de datos

<img src="https://raw.githubusercontent.com/JoshuaMeza/CodePain_POO/master/Recursos/DataBase.jpg" witdh=30% margin=auto>