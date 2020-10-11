This project is a mix of two known projects implementing the elk stack on docker. 

Here is the main project
https://github.com/deviantony/docker-elk
Consult with it README1.md

The main project has been enhanced with security features found in another project
https://github.com/sherifabdlnaby/elastdocker
Consult with it README2.md

The following commands should be used to start the project:

docker-compose up
docker-compose exec -T elasticsearch bin/elasticsearch-setup-passwords auto --batch

The given passwords should be use to replace hardcoded passwords in the app

make setup
make elk