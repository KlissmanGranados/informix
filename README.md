# Informix database

A container that contains an Informix database with its default configurations, using the official IBM image.


## Connection


| Parameter | Value    |
|-----------|----------|
| user      | informix |
| password  | in4mix   |
| database  | sysadmin |
| server    | informix |
| port      | 9088     |

## Default compose file:
    docker-compose.yml

## Quickstart Steps

### Pre-requisites
1.  docker
2.  docker-compose

### Start docker compose:
1.  cd to project directory 
2.  On Unix, run __chmod -R 777 *__ 
    On Windows, make sure all drives are shared in docker
3.  Run __docker-compose up__


### Up & Running 

### Stop and remove Containers & volume
1. Run __docker-compose down -v__ 

