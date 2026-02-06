git clone project 
cd taskmanagerpro
mvn clean install 
cd target
java -jar task-manager-1.0.0.jar
nohup java -jar task-manager-1.0.0.jar > app.log 2>&1 &
Application run on port 8081


using docker-compose 
docker-compose up -d
