1- clone

2- run `docker-compose up -d`

3- run `docker login http://localhost` and provide username and password (default: admin/password).

4- Your private registery is ready

5- To test, navigate to: `http://localhost/v2`


Note: credentials are stored in `auth/registry.password` file, and in "apache .htpasswd" format