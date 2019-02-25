# laravel-vue-photos

https://www.hypertextcandy.com/vue-laravel-tutorial-introduction/


## Install

```
git clone https://github.com/katsuhiko/laravel-vue-photos.git
cd laravel-vue-photos

docker run --rm -v $(pwd):/home/app -w /home/app node:8.12 npm install

docker-compose up -d
docker exec -it app /bin/bash
php composer.phar install
```


 ## Develop

```
docker-compose up -d
```

```
docker-compose down
```


## DB

```
docker exec -it db /bin/bash
mysql -u root -p
CREATE DATABASE photos DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_bin;
```


## Test

```
docker exec -it app /bin/bash
./vendor/bin/phpunit --testdox
```
