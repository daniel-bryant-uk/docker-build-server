docker-machine create buildserver --driver virtualbox --virtualbox-disk-size "50000"

docker run -p 9090:8080 -p 50000:50000 -v /Users/danielbryant/Documents/dev/build-server/jenkins_home:/var/jenkins_home jenkins 
