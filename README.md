# Sistema-de-reserva1

## Sistema-de-reservas-de-sala
-El instituto desea implementar un sistema digital para estudiantes y personal puedan reservar salas de estudio
## Nombre:Luis-Riquelme

## Diagrama de caso de uso

-Dentro del caso uso se observa falta  dentro del Estudiante no tiene lógica en si que el estudiante tenga acceso a otro historial de otras personas, tampoco a ver historial de reservas ya que eso lo deberia ver el administrador

- Dentro del diagrama de caso de uso se aprecia falta de Extend y include 

- Los actores APIreservaExterna y sistema de notificaciones no cumplem el perfil de actores 


## Diagrama de clases 
- Las clases no pueden estar solas "Volando"
- - No se encuentra ningun patron de diseño 
-Las clases no tienen relación 
- El administrador no deberia interactuar con el usuario, más bien con el sistema de reserva 

## Diagrama de implementacion 
- El nodo donde esta el administrador no esta definido ni  mencionado 
-  el gestor de notifcaciones aplicando el patron brigde es sufuciente, no necesita conectar otro nodo 
- La dispnibilidad de la sala deberia ser gestionada por el admin, no por una apa,esto complementa el primer error encontrado 
-Las líneas cruzadas entre el “Formulario de Reserva”, “Base de Datos Central” y “Sistema de Gestión de Reservas” estan desorientadas y visualmente confunde 
