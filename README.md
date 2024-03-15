Rodar docker em profile "dev"
docker run -d -p 8080:8080 -e PROFILE=dev bielcx/fiap-checkpoint1

Rodar docker em profile "stg"
docker run -d -p 8080:8080 -e PROFILE=stg bielcx/fiap-checkpoint1

Rodar docker em profile "prd"
docker run -d -p 8080:8080 -e PROFILE=prd bielcx/fiap-checkpoint1
