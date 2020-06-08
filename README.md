Example Voting App
=========

Fork directo de [here](dockersamples/example-voting-app).

Arquitectura
-----

![Architecture diagram](architecture.png)

* App en phython que permite votar entre 2 opciones
* Una cola en Redis que recolecta los votos
* Un worker en .NET que toma los votos de la cola y los almacena en...
* Una BDD Postgres que almacena los votos en un volumen Docker
* Una app web en node que muestra los resultados de los votos en tiempo real

