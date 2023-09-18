# Laravel
[A containerized laravel application](https://github.com/laravel/laravel.git), that has been containerized and deployed

## Prerequistes
* Docker and Docker Compose Installed

## Getting Started
1. Clone the repository

```
git clone https:github.com/Ayomide05/Laravel.git
```
2. navigate to the project directory

```
cd Laravel
```
3. Start the docker containers

```
docker compose up -d
```
4. Navigate to the app service( php service) container

```
docker exec -it app /bin/bash
```
5. Install Composer

```
Composer Install
```
6. Generate php application key

```
php artisan key:generate
```
7. Access the application at **'http://localhost:8080'** 

