### With Docker Compose (mongodb, mongo-express and application)

#### To start the application through docker image

Step 1: start mongodb, mongo-express and application

    docker-compose -f docker-compose.yaml up
    
_You can access the mongo-express under localhost:8080 from your browser_
    
Step 2: access the nodejs application from browser 

    http://localhost:3000

Step 3: start mongodb, mongo-express and application

    docker-compose -f docker-compose.yaml down

