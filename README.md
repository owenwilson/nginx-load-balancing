# Nginx - Virtualhost - Loadbalancing - Docker - Docker-compose

###Nota

- Remember to have nginx installed on your linux host and copy the **example-vhost-nginx** file to **/etc/nginx/site-available/** and then create a symbolic link.

```sh
ln -s /etc/nginx/site-available/example-vhost-nginx /etc/nginx/site-enabled/
```

- Before you launch the docker-compose command to create the my-net network with the following command:

```sh
docker network create my-net
```

- Now execute command compose docker

```sh
docker-compose up -d
```

- Open browser to add Ip address
