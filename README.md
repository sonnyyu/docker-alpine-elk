docker build -t docker-elasticsearch elasticsearch/

docker build -t docker-kibana kibana/

docker build -t docker-logstash logstash/

docker-logstash        latest              b01f1f3259e0        25 seconds ago       393MB

docker-kibana          latest              9da598d844fd        About a minute ago   242MB

docker-elasticsearch   latest              b7fb436422bb        2 minutes ago        193MB

docker-compose  config

docker-compose build

docker-compose up -d
