# Docker Compose Guide

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

## The `services:` Block

The `services:` block defines the containers that make up the application. In this activity, there are two services: `database` and `app`.

The `database` service uses MariaDB 10.6 to provide the database for Nextcloud.

The `app` service uses the Nextcloud image and provides the web application through port 8080.

## How Nextcloud Finds the Database

Nextcloud finds the MariaDB database using the `MYSQL_HOST` environment variable.

The value is:

```text
MYSQL_HOST=database