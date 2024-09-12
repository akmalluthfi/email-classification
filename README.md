# Email Classification

How to run this project:

## Clonning from repo

Using Https

```bash
git clone https://github.com/akmalluthfi/email-classification.git
```

Using SSH

```bash
git clone git@github.com:akmalluthfi/email-classification.git
```

## Setup Project

Download dependencies

```bash
composer install
```

Copy .env-example

> Setting your environment

```bash
cp .env-example .env
```

Generate app key

```bash
php artisan key:generate
```

Migrate database and seeder the database

```bash
php artisan migrate --seed
```

## Run program

```bash
php artisan serve
```

## API Documentation

You can view the api documentation at:
[https://documenter.getpostman.com/view/19353108/2s9YsDkv2F](https://documenter.getpostman.com/view/19353108/2s9YsDkv2F)

## Login

username: admin@media.pens.ac.id <br>
password: password
