# Laravel Project

## Pull Laravel Boilerplate Code

- If first time creating a GitHub repo:

https://dev.to/sourcegraph/creating-a-new-laravel-application-with-sail-and-docker-no-php-required-4c2n

## Prerequisites

1. Install php
2. Install composer
3. Install Docker Desktop

## VS Code Extensions

To make development experience easy, these extensions are very helpful:

1. PHP Extension Pack by Xdebug
2. PHP by DEVSENSE

## Run Server

1. Run Docker Desktop

2. Run server commands
    ```zsh
    cd ./laravel-proj
    npm run dev
    ```

## NPM Command Arguments

- Always use `--` to connect `npm run sail` and `artisan` for example -> `npm run sail -- artisan` = `./vendor/bin/sail artisan`
- Or connect `artisan` with further cli options like: `npm run artisan -- make:model --help` or `npm run artisan -- --help`

https://stackoverflow.com/questions/11580961/sending-command-line-arguments-to-npm-script

## Laravel Resources

### App Structure

https://laravel.com/docs/10.x/structure


### Basic Tasks with Laravel (v5.2)

Even though it's version 5.2, many ideas are still valid for version 10.x

https://laravel.com/docs/5.2/quickstart#defining-the-layout

### Basic Laravel API

https://blog.treblle.com/how-to-create-rest-api-using-laravel/#3-make-a-model-and-migration

### Laravel Update Migrations

https://makitweb.com/how-to-update-table-structure-using-migration-laravel/#google_vignette
