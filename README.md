After cloning this repo install node js and related dependencies
then open docker and pull mongo and mongo-express from docker CLI
then run the below commands to create network and run the mongo and mongo-express with the given commands
docker-compose -f mongo.yaml down

then open localhost:8081 to open mongo-express GUI and then create a database user-account and then create collection users 
then run localhost:3001 and update the user profile and to see the results open mong0-express GUI
