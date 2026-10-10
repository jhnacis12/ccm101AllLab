# Multi-Tier Architecture

This document will explain the two-tier architecture used by the Nextcloud and MariaDB deployment.

## The Web/Application Tier

The web/application tier will use Nextcloud to provide the user interface and handle HTTP requests.

## The Database Tier

The database tier will use MariaDB to store persistent application data.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container can perform its own specific role.
