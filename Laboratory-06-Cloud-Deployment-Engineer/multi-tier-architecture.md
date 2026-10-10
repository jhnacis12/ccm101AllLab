# Multi-Tier Architecture

## What is Two-Tier Architecture?

A Two-Tier Architecture is an application structure where the system is divided into two main parts: the Web/Application Tier and the Database Tier. In this mission, Nextcloud will serve as the web application while MariaDB will serve as the database.

## The Web/Application Tier

The Web/Application Tier is responsible for providing the application interface to users and handling HTTP requests. In this project, the Nextcloud container acts as the Web/Application Tier. Users access Nextcloud through a web browser.

## The Database Tier

The Database Tier is responsible for storing persistent data needed by the application. In this project, MariaDB acts as the Database Tier and stores information such as user accounts and application data.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and maintain. Each container has a specific responsibility, and the database can operate separately from the web application. This also makes the architecture more organized and easier to deploy using Docker Compose.
