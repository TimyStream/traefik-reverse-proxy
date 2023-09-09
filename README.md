# Ready to go Traefik Reverse Proxy

## Software needed
- [Docker](https://www.docker.com/)
    - [Docker Desktop](https://docs.docker.com/desktop/)
    - [Docker Engine](https://docs.docker.com/engine/)
- [Traefik Proxy](https://traefik.io/traefik/)

## Install
1. Clone the repository to the server
2. Copy the .env.example to .env
3. Edit the .env file to your liking
4. Create the Docker network "webProxy"
    ```BASH
    docker network create webProxy
    ```
5. Spin up the proxy
    ```Bash
    docker compose up -d
    ```
