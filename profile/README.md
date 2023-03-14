# Welcome to Dockerize React Project, 

My Name is **Deni Setiawan**, I am **Backend Dev & System Analyst** at http://nexsoft.co.id/ from Indonesia.
**Loves writing and coding enthusiast** who always **keeps learning** about software engineering skills for make me **keep an update and strenghts skills** 🚀


### About Me
| Profile     | URL                                                          | 
|------------------|--------------|
| Github | https://github.com/denitiawan |
| Medium | https://deni-setiawan.medium.com/ |

# 1. what is 'Dockerize React Project'
Here we will learning how to dockerize React project for make simplify the development and testing. our application will running well, no matter with different machine or computer, because application will running on docker container.

### 1.1. Overviews
- Created simple web C-PANEL application used react.js
- Interactive Login and Dashboard page include communicated to backend server
- Implementat a Dockerfile on react project, for creating the docker image 
- Implement push docker image to dockerhub [https://hub.docker.com/repositories/denitiawan](https://hub.docker.com/repositories/denitiawan)
- Implement docker-compose, for configure, setup and running the application (frontend & backend)
- testing Frontend & Backend

### 1.2. Frontend (Web)
`React.js`
`Redux Multi Store`
`i18n Multi Resource`
`Router`
`Secure Routing`
`Error Boundaries`
`Variable Environtment .env`
`React Hook`
`Functional Component`
`Loggin`
`axios`
`Docker`
`Docker-compose`


### 1.3. Backend
`Springboot 2.7^`
`Java 11`
`Spring Security`
`JWT `
`Oauth0`
`Mysql`
`liquibase (database migration)`
`cors`
`Docker`
`Docker-compose`

### 1.4. Repositories
| Project Name     | Visibility     | Description  | URL Repository                                                          | 
|------------------|--------------|--------------|-------------------------------------------------------------------------|
| drp-documentation | private | Documetation Project | https://github.com/denitiawan/drp-documentation                                        |
| drp-web | private | Web project | https://github.com/denitiawan/drp-web                                         |
| drp-backend | private | Backend Project | https://github.com/denitiawan/drp-backend          

# 


# 2. Run application using Docker Compose
- clone `setup` repository on this link https://github.com/dockerize-react-project/setup
- after clone, open folder `./drp-documentation/drp` in `terminal` or `cmd`
- on `terminal` or `cmd` type this commands `docker-compose up -d`
- wait until all aplication running well

## 2.1. Test Frontend 
| container | URL   | client access | username | password |
|--------|--------|--------|--------|--------|
| drp-web | http://localhost:3001 | browser | admin | admin |

## 2.2.  Test Backend
| container     | URL      | client access |
|--------|--------------|--------------|
| drp-backend | http://localhost:8181 | postman or http client |
| drp_mysql | http://localhost:3308 | terminal or Sql client  |
| drp_redis | http://localhost:6379 | terminal or Redis client |


### 2.2.1.  Mysql CLI
- open cmd
- type `docker container exec -it drp_mysql  mysql -u user -p` enter
- type `password`
- choose db_drp


### 2.2.2. Redis CLI
- open cmd
- type `docker container exec -it drp_redis  redis-cli -h 127.0.0.1 -p 6379 -a "password123"` enter
- see all keys `keys *`
- get by key `get <keyname>`
- set key `set <keyname> <value>`
- see TTL `ttl <keyname>`

### 2.2.3.   Api Collection (Postman)
- see on this link [DRP.postman_collection.json](https://github.com/dockerize-react-project/postman/DRP.postman_collection.json)

| Name | URL | Method | body |
|--------|--------|--------|--------|
| Login | http://localhost:8181/login  | POST |{"username":"admin","password":"admin"} |
| . . . | . . . | . . . | . . . |



