# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
Dockerfile for alpine nginx per-confiugured with proxy-pass and NASXI(WAF)

* Version
Nginx 1.9.12
NAXSI lastest  

* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
Build && run

* Configuration
1. -p 80:80 -p 443:443 
2. -e DOMAIN=www.myawesomedoamin.com
3. -e BACKEND_SITE=10.1.1.1
4. -e SSL_CER=domain.crt
5. -e SSL_KEY=domain.key
6. -e SSL_DH=domain.pem

* Dependencies
docker

* Database configuration
none

* How to run tests
docker run -d -p 80:80 your-registry-site/docker-nginx-proxy 

* Deployment instructions
docker run -d -p 80:80 your-registry-site/docker-nginx-proxy 


### Contribution guidelines ###

* Writing tests
What ever you want

* Code review
What ever you want

* Other guidelines
What ever you want

### Who do I talk to? ###

* Repo owner or admin
me

* Other community or team contact
me