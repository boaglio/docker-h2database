docker build -t h2  .

docker tag h2 boaglio/h2

docker push boaglio/h2:latest
