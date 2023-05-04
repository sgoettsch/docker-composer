# Docker Composer

Simple docker images containing installed version of composer o run composer commands without the need to install it. Supports different PHP Versions.

### Example Commands:

- PHP 8.2:
```docker run --rm --mount type=bind,src=$(PWD),target=/app ghcr.io/sgoettsch/docker-composer:latest-php8.2 composer install --working-dir=/app```

- PHP 8.1:
```docker run --rm --mount type=bind,src=$(PWD),target=/app ghcr.io/sgoettsch/docker-composer:latest-php8.1 composer install --working-dir=/app```

- PHP 8.0:
```docker run --rm --mount type=bind,src=$(PWD),target=/app ghcr.io/sgoettsch/docker-composer:latest-php8.0 composer install --working-dir=/app```