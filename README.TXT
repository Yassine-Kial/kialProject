YOU SHOULD BUILD two containers for each database, use docker file for each one of them





for each database create image:

commmand :docker build -t mypostgres:16 .



for data_db container run  :

docker run -d -p 7777:5432 --name mypostgres-container mypostgres:16
 

for auth_db container run : 

docker run -d -p 6666:5432 --name mypostgres-container mypostgres:16



NOTEZ BIEN mappage de port 7777 pour data database et 6666 pour authentification database




