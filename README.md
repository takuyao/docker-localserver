# docker-localserver

## What is this?

- Execute the following development support service in local PC.
  1. Gitbucket
  1. Redmine
  1. Jenkins
- We can access via one host url by reverse proxy.

## How to use it?

1. Change `MYSQL_ROOT_PASSWORD` in `docker-compose.yml`.
1. Execute `docker-compose up -d`.
1. Open `http://<YOUR IP ADDRESS>/index.html`.
