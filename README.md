run command:
docker compose up -d

for entering in mysql terminal:
docker exec -it <container_id> sh
or
docker exec -it <container_id> bash

to run mysql terminal:
mysql -u <user_name> -p <_password>

port is 3307 because on my machine it was already occupied.
