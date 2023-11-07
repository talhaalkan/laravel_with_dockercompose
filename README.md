# laravel_with_dockercompose
Set Up Laravel with Docker Compose on Ubuntu 22.04

How To Install and Set Up Laravel with Docker Compose on Ubuntu 22.04

Introduction
To containerize an application refers to the process of adapting an application and its components in order to be able to run it in lightweight environments known as containers. Such environments are isolated and disposable, and can be leveraged for developing, testing, and deploying applications to production.

In this guide, we’ll use Docker Compose to containerize a Laravel application for development. When you’re finished, you’ll have a demo Laravel application running on three separate service containers:

An app service running PHP7.4-FPM;
A db service running MySQL 5.7;
An nginx service that uses the app service to parse PHP code before serving the Laravel application to the final user.
To allow for a streamlined development process and facilitate application debugging, we’ll keep application files in sync by using shared volumes. We’ll also see how to use docker-compose exec commands to run Composer and Artisan on the app container.


source:
https://www.digitalocean.com/community/tutorials/how-to-install-and-set-up-laravel-with-docker-compose-on-ubuntu-22-04
