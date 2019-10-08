# Welcome to Java Docker World

### Build a simple docker image containing openJDK 11 and 'HelloDocker' java class
	docker image build -t java-in-container/hellodocker:0.1 .

### Run a docker image
	docker run --name hellodocker java-in-container/hellodocker:0.1

### Start the container
	docker start -a hellodocker

### Check contianer logs
    docker logs hellodocker

### Remove container
	docker rm hellodocker