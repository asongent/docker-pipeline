# This project basically teaches you how to build or push a project from Github repo to Dockerhub

---
# Docker image will be built in docker registery once this project is pushed to our docker repo


---


##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    