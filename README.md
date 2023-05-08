##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
[![Java CI with Gradle](https://github.com/vthotigar-cscc/week10-thotiv1-my-project/actions/workflows/ci.yml/badge.svg)](https://github.com/vthotigar-cscc/week10-thotiv1-my-project/actions/workflows/ci.yml)
