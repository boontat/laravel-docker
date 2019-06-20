## Remark

Follow from tutorial [Dockerize laravel](https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose)

## Pre-requisite
Docker

Docker compose

## Installation
git clone the repository <project_name>

docker run --rm -v $(pwd):/app composer install

sudo chown -R $USER:$USER <project_name>

## Usage
cd <project_name>

docker compose up -d

## Security Vulnerabilities

If you discover a security vulnerability within project, please send an e-mail to boontat via [monkpuah123@gmail.com](mailto:monkpuah123@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
