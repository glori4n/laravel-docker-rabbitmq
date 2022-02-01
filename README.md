<p align="center"><img src="https://github.com/glori4n/laravel-relationships-exercise/blob/master/public/images/glogo.png"></>

# laravel-docker-rabbitmq
This project is an exercise exploring Docker and its usage with Laravel, alongisde RabbitMQ, it contains three laravel projects, in which they will function as one, <b>messageOut</b> will send out a message to <b>messageIn</b> project, whereas the third project containing RabbitMQ will be the one responsible for the communications between the two.


# Installation
1. Clone the repository or download it;
2. Make a copy of the <b>.env.example</b> file in the same location with the name <b>.env</b> for each of the projects;
3. Adjust the .env according to the docker-compose.yml for each of the projects;
4. Run composer up -d for each of the projects.
