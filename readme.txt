build - docker build -t test/simple-backend .

list images - docker images

run  - docker run -p 4000:4000 test/simple-backend

for all the container thar are running currently info - docker ps
to stop all the containers that are running currently - docker-compose stop

stop - docker stop ${containerid}

kill - docker kill ${containerid}

push - docker push

build all images - docker-compose build

to start in an order - docker-compose up -d mongo 
                    - docker-compose up -d app 
                    - docker-compose up -d client


error - if mongo is already running - docker kill 

Stop and remove the containers - docker compose down