# mongo-compose
Just a simple docker compose for mongo

## How to use it

1. Get the code:  
    - `git clone https://github.com/mpuccini/mongo-compose.git` **OR** 
    - download the zip file from the [public repository](https://github.com/mpuccini/mongo-compose) 
    - move to the folder
2. Configure root user:  
    - `copy env.sample .env` 
    - edit the .env file   
3. Start container:  
    - `docker compose up -d` 
    
> Note: by default the mongo 4.2 version (image official supported by DockerHub) is used. Modify the `image` section inside the `docker-compose.yml`file to get your preferred version.
> If you set just `image: mongo` you will get the latest one.
> If you prefer to use the container image version officially supported by MongoDB, please refer to the [official documentation](https://www.mongodb.com/docs/v6.0/tutorial/install-mongodb-community-with-docker/) for more.
