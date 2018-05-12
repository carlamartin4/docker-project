# docker-project

**TO DO**

- [X]  Create repo and readme.md
- [X]  Create docker-compose.yml
- [X]  Create a tk domain
- [X]  Nginx reverse proxy
- [X]  Let's Encrypt SSL

Docker-compose.yml:

- Unique document with three services: web, erp and drive. 
- It include volumes, which permit not to lose information.
- It include ports, which indicates the port inside the docker and also the one which go outside (the one from your computer).
- It include dependences, which are other services that our service need (for example, sql database).

Nginxe revers proxy:

- It is included inside the docker-compose.yml
- It allow us to give names to the ports (so it is easier to remember them).
- We have created a domain called savebirds.tk so with proxy we obtain: erp.savebirds.tk, www.savebirds.tk and drive.savebirds.tk.
- It gives SEO (Search Engine Optimization).

Let's Encrypt

- It gives SSL certificates, so it allow secure connections.
