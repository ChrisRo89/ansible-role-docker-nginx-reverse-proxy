# ansible-role-docker-nginx-reverse-proxy
Contains a ansible role to setup an NGINX Reverse Proxy with Let's Encrypt in an docker environment
The playbook is based on the following two docker images: 
* [Docker Image - jwilder/nginx-proxy] https://hub.docker.com/r/jwilder/nginx-proxy/
* [Docker Image - jrcs/letsencrypt-nginx-proxy-companion] https://hub.docker.com/r/jrcs/letsencrypt-nginx-proxy-companion/
The docker images are very helpfull; this playbook prepares two docker containers and an own bridge network. 
