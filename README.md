![Laravel with Docker](https://user-images.githubusercontent.com/27271223/61190265-f8c9b600-a6ae-11e9-8b04-3998fae4687b.png)



# Laravel with Docker
A docker-compose file for laravel applications with dockerfile.


## Requirements
As you know you must install Docker with Docker-compose, In order to install these packages you can follow these links:
- [Install Docker CE](https://docs.docker.com/install/)
- [Install Docker-Compose](https://docs.docker.com/compose/install/)


## Usage

That's very easy, Just clone the project and pass 2 steps:
1. Go to root of the project.
2. run `docker-compose up -d`.
3. run `docker-compose exec app composer create-project --prefer-dist laravel/laravel .`

Enjoy it ...


