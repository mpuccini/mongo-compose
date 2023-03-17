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
    
> Note: by default a 4.2 version for mongo is used. Modify the `image` section inside the `docker-compose.yml`file to get your preferred version.
> If you set just `image: mongo` you will get the latest one.
