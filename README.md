# laravel-vue-photos

https://www.hypertextcandy.com/vue-laravel-tutorial-introduction/

# install

```
git clone https://github.com/katsuhiko/laravel-vue-photos.git
cd laravel-vue-photos
docker run --rm -v $(pwd):/var/www/html -w /var/www/html hiroshimasymphony/php-fpm-base:7.2-stretch ./composer.phar install
docker run --rm -v $(pwd):/home/app -w /home/app node:8.12 npm install
```

```
docker-compose up -d
```

```
docker-compose down
```
