## Verification Commands

- Run test container
  ```sh
  docker run hello-world
  ```

- Run a Nginx web server and expose it on http://localhost:8080
  ```sh
  docker run --rm --name some-nginx -p 8080:80 nginx
  ```
  - `--rm`: Delete image after run
  - `--name`: A custom name for the container
  - `-p 8080:80`: Expose the port inside the container to the host
    - `8080`: The host port
    - `80`: Port on the inside of the container

## Docker Compose Commands

- Start an application stack

  ```sh
  docker compose up
  ```

## Reference

- [Docker Hub Container Registry](https://hub.docker.com/)
