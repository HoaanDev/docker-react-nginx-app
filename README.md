# docker-react-nginx-app
ReactJS &amp; nginx web server docker image 
<hr/>

  ## Docker image build command
    ```
    docker build -t react-nginx-server .
    ```

  ## Docker image run command
    ```
    docker run --name react-nginx-app -p 8080:80 -d react-nginx-server
    ```

  ## Docker compose command
    ```
    docker compose up
    docker compose up -d
    ```
