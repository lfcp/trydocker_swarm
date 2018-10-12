# trydocker_swarm

Read lfcp/trydocker first.


Attention: 

This file sets up 4 containers, 3 of which contain the webapp and REST API.
Resources used for the webapp: cpu: 0.3, memory: 1500M.

 Usage:
 Make sure you have Docker-Machine installed first.
 Clone this repository to a folder in your machine.
 Change directory to the folder of this repository in your machine.
 Make sure you have a docker swarm setup.
 Run on your manager the following command: "docker stack deploy -c docker-compose.yml app"
 Access http://<ip>:5000/personmanagement/ on your favourite browser and have fun!

Notes:
This is a completed exercise to learn how to use Docker.
Everytime the database container is loaded, it will be automatically populated with data.
