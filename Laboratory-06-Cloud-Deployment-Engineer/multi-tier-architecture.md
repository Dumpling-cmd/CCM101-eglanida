# Multi-Tier Architecture

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

## What is Two-Tier Architecture?

A two-tier architecture separates an application into two main tiers: a web/application tier and a database tier. In this laboratory, Nextcloud acts as the web/application tier while MariaDB acts as the database tier.

## Web/Application Tier

The web/application tier handles user requests and provides the application's web interface. In this activity, the Nextcloud container provides the private cloud storage interface that users access through a web browser.

## Database Tier

The database tier stores persistent information required by the application. In this activity, MariaDB stores Nextcloud's database information, including user accounts and file metadata.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container can perform its specific role, and the database can be managed independently from the web application.