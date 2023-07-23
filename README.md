# dev-auth a configurable OpenID Connect sever for on laptop development

OpenID Connect (OIDC) is the most widely used authentication standard in 2023. All
the leading frameworks make it very easy to configure single sign on, or 
resources servers. 

While developing on a laptop without internet how do you get access to an 
OIDC server that you can easily configure for local testing. Production quality 
OIDC server tend to be quite complex to configure locally or offered as SaaS 
services that will not work when you don't have an internet connection.

`devauth-server` is a simple to configure and run OIDC server that you can run
on your laptop while coding other service that have a dependency on an OIDC
server. `devauth-server` is insecure should only ever be run on a laptop.

`devauth-server` is a Spring Boot 3.1 application based on the Spring 
Authorization Server project, published as a container image that you can
configure using environment variables in a `docker-compose.yaml` file.

## User Guide


## Development Guide

If you want to extend or customize `devauth` you will need Java 17 and Java IDE
import the project and start hacking, the project is a multi module maven 
project following all the typical conventions of a spring boot project.
