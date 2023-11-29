Django Docker NGINX AWS

for local:
 in the docker-compose.yml location run: sudo docker-compose up -d --build
  if the build and up command not failed then
  check on browser localhost:8000

for production:
  in the docker-compose.prod.yml location run: sudo -f docker-compose.yml.prod up -d --build
  if the build and up command not failed then
  check on browser localhost:1337
