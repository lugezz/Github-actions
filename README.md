##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t demo-java-app .
    
##### push image to repo 

    docker tag java-app demo-java-app:java-1.0
    
