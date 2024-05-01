Example os use of MISP server with DOCKER COMPOSE and including NGINX and CERTBOT to create and renew the certificates.

You need configure DNS and FIrewall to access to you server por 80 and 443.


### If you need letsencrypt certificate run the next line.
Them run init-letsencrypt for create the certificates.

### If you use personals certificate please put into the SSL (/data/ssl) directory and uncomment the lines inside /data/nginx/app.conf
And them RUN docker-compose up -d to ejecute MISP in secure way