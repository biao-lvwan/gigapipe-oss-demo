docker-compose -f docker-compose.yml up -d 

docker build -t dockerregistry:30290/dummy-exporter:latest -f Dockerfile .

docker build -t dockerregistry:30290/dummy-server:latest -f Dockerfile .