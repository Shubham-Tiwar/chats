Live Staging URL: http://18.175.55.242/

    Architecture Summary: Brief overview explaining how Nginx proxies HTTP traffic and WebSocket requests to the FastAPI backend.

    Bug Fixes Summary:

        Uvicorn Host Binding: Updated --host from 127.0.0.1 to 0.0.0.0 in Dockerfile.

        Static File Mounting: Uncommented frontend volume mount in docker-compose.yml.

        WebSocket Routing: Configured Upgrade and Connection headers in nginx.conf.

    Deployment Instructions: How to run the app using docker compose up -d --build.
