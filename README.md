# comandos-docker

-- Stop em todos os containers
docker kill $(docker ps -q)

-- Remover todos os containers 
docker rm $(docker ps -q)

-- Remover todos os containers forçando mesmo se ele estiver ativo
docker rm -f $(docker ps -q)




--Utilize o comando images para listar:
docker images

--subir docker-compose
docker-compose up -d






