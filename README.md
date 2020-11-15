# GoAPI

A simple phonebook app using Golang and GORM.

# Development: Getting Started

# Requirement

* go 1.13+
* PostgreSQL
* Docker
* Docker Compose

Clone Project

```bash
$ git clone https://github.com/codephilics/go-phonebook.git
$ cd go-phonebook
```

Create .env: 

```bash
$ nano .env
```

Set .env values: 

```bash
POSTGRES_URL=postgres://postgres:yourpassword@postgres/postgres?sslmode=disable
PORT=8080
```

To run the project

```bash
$ docker-compose up
```
