# This project basically teaches you how to build and push docker image to Docker registry

---
# Docker image will be built in docker registery once this project is pushed to our docker repo


---


##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
