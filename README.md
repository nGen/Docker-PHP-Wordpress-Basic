# PHP Basic wordpress - using Docker

## Getting started.

* Create a copy of `.env.dist` and modify the details as needed.
* Run `docker compose up -d` to start the containers.
* Navigate to `http://localhost`. 
    * However, If you have changed the `WP_APP_PUBLIC_PORT` in the `.env`, navigate by point to that point. e.g. if `WP_APP_PUBLIC_PORT` is set to `8080`, then navigate to `http://localhost:8080`
* You should now be greeted with the configuration screen. 