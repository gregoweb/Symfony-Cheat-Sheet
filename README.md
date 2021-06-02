# Symfony Cheat Sheet

## Project creation
- symfony new ProjectName --full
- symfony new Name_Generator

## Web server
- symfony server:start
- symfony server:stop
### start in background
- symfony serve -d
### SSL cert install
- symfony server:ca:install

## Controller generation
- symfony console make:controller ControllerName

## Doctrine
### Create Table / Entity
- symfony console make:entity EntityName
### generate migration file
- symfony console make:migration
### apply migration to database
- doctrine:migrations:migrate 

## Doc
- https://symfony.com/doc/current/index.html
- https://symfony.com/doc/current/the-fast-track/en/index.html
- https://symfonycasts.com/

## Symfony console
### List make commands of Symfony console
- symfony console list make

## EasyAdmin
- https://symfony.com/doc/current/the-fast-track/en/9-backend.html

## Managing Environment Configurations
- https://symfony.com/doc/current/the-fast-track/en/5-debug.html

## Twig
- https://symfony.com/doc/current/page_creation.html#creating-a-page-route-and-controller
- https://symfony.com/doc/current/templates.html

## Search for known security holes
-symfony check:security
