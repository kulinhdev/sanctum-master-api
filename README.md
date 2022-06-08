#### Author: Phạm Ngọc Linh
<phamlinhaz229@gmail.com>

### Run docker laravel with nginx

- docker build -t app:latest .

- docker run -d -p 80:80 app:latest

- http://localhost


##### Exec bash into container 

docker exec -it <container id> bash 

cat /etc/os-release
