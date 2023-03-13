# Welcome to Dockerize React Project Organization, 

My Name is **Deni Setiawan**, I am **Backend Dev & System Analyst** at http://nexsoft.co.id/ from Indonesia.
**Loves writing and coding enthusiast** who always **keeps learning** about software engineering skills for make me **keep an update and strenghts skills** 🚀


### About Me
| Profile     | URL                                                          | 
|------------------|--------------|
| Github | https://github.com/denitone |
| Medium | https://deni-setiawan.medium.com/ |

## what is 'Dockerize React Project' organization
this organization for learning how to dockerize React project for make the development and testing so easy and simple.
 
### Overviews
- implementation Dockerfile on React project
- Build docker image from React project
- push docker image to dockerhub
- Create docker compose for setup the container 
- run and testing the app

### Repositories
| Project Name     | Visibility     | Description  | URL Repository                                                          | 
|------------------|--------------|--------------|-------------------------------------------------------------------------|
| drp-documentation | public | Documetation Project | https://github.com/denitone/drp-documentation                                        |
| drp-web | private | Web project | https://github.com/denitone/drp-web                                         |
| drp-backend | private | Backend Project | https://github.com/denitone/drp-backend          

## Technologies
### drp-web
- React.js

### drp-backend
- Springboot 2.7^
- Java 11
- Spring Security
- JWT 
- Oauth0
- Mysql
- liquibase (database migration)
- Docker



# Run application using Docker Compose
- clone `drp-documentation` repository on this link https://github.com/denitone/drp-documentation
- after clone, open folder drp-documentation/drp in `terminal` or `cmd`
- on `terminal` or `cmd` type this commands `docker-compose up -d`
- wait until all aplication running well

# Test and run application
| container     | URL      | SYNTAX CLI 
|--------|--------------|--------------|
| drp-web | https://localhost:3006 |  |
| drp-backend | https://localhost:8686 |  |
| drp_mysql | https://localhost:3308 | docker container exec -it drp_mysql /bin/sh mysql -u user -p password |
| drp_redis | https://localhost:6379 | docker container exec -it drp_redis /bin/sh redis-cli -h localhost -p 6379 -a "password123" |


#


