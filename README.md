# API test SOHO

## Configuración de instalación

```bash
# clone repository
$ git clone https://github.com/JavierPinzon34/apiSoho.git

# install dependencies
$ composer install

# config .env
$ cp .env.example .env

# generate key app laravel
$ php artisan key:generate

# load data in BD
$ php artisan migrate --seed

# launch server in local
$ php artisan serve
```
