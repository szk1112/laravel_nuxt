## Usage
```bash
docker-compose build
docker-compose run --rm php-fpm sh -c "cp .env.example .env; composer install;php artisan migrate"
docker-compose up -d
```
