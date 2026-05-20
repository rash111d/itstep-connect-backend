# ITSTEP Connect Backend

Backend часть проекта ITSTEP Connect.

## Stack

- Go
- Gin
- PostgreSQL
- GORM
- JWT

## Features

- Register
- Login
- JWT Authentication
- Posts CRUD
- Comments CRUD
- Protected Routes

## Run project

```bash
go run cmd/main.go

Database

PostgreSQL:

dbname: itstep_connect
user: postgres
password: 123
port: 5432
API Routes
Auth

POST /register

POST /login

Posts

GET /api/posts

POST /api/posts

DELETE /api/posts/:id

Comments

POST /api/comments

GET /api/posts/:id/comments

DELETE /api/comments/:id


---

# Потом сохранить

```text id="w6m2q8"
Ctrl + S