# Docker Scripts Collection
In this Git repository I intend to record some applications of interest for server management, continuous integration systems and other interesting tools.

They are tested and work for my server or in my tests, which doesn't mean they need any extra configuration if you can't get them to work under your own circumstances.

## Kong y Konga

Kong is a gateway that allows the capture of requests and their derivation to different environments or containers. This way it will seem that several microservices or different APIs are in the same place.

On the other hand, Konga is a visual manager for Kong, and allows to create and edit services, routes, certificates and so on without having to write the commands in the command console.

The docker-compose is delivered with the containers for these applications, plus another container for the database that Kong uses to save the information, another one for database preparation and a last one for Konga preparation. 

## Portainer
Portainer is a visual manager for the management of everything related to Docker. It allows to manage images, containers, stacks and services from a comfortable visual web interface

## Portus y Docker-Registry
Docker-Registry is the official Docker tool for storing images on a private server in the same way that Docker Hub works. It allows users to push and pull from an image repository. However, this application does not control access permissions.

To fill this gap, Portus is used. Portus allows you to create authorised users, allowed namespaces and ultimately control which users have access to which images.
