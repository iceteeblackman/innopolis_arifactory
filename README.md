# innopolis_arifactory

docker volume create artifactory-data
docker pull docker.bintray.io/jfrog/artifactory-pro:latest
docker run -d --name artifactory -p 8082:8082 -p 8081:8081 -v artifactory-data:/var/opt/jfrog/artifactory docker.bintray.io/jfrog/artifactory-pro:latest 
