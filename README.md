# Getting Started - Local Development

## Installation

To get started locally, follow these instructions:

1.  make sure you have the latest Nodejs installed
2.  `npm install` to install dependencies
3. download postgres and create database and create table 
```
CREATE DATABASE task_management_system;

```
```
CREATE TABLE tasks (
    id SERIAL PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    description TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

```
## Compiles and hot-reloads for development
```
npm run serve
```