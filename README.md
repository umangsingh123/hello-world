# hello-world
Simple Spring Boot Project for Demo. Runs on Port 8090.

# To run the app use the below steps .
1. mvn clean
2. mvn install

# For Containerization use the below steps .
1. docker build -t $USER/hello-world:0.0.1 .  
2. docker run -p 8090:8090 -t $USER/hello-world:0.0.1 