# Docker-anyproxy

Docker for Anyproxy - a fully configurable http/https proxy in NodeJS, which offers you the ablity to handle http traffic as you wish.

# RUN
```bash
docker run -d --name anyproxy -p "8001:8001" -p "8002:8002" -p "8003:8003" -p "8088:8088" anyproxy
```
and open Web UI http://127.0.0.1:8002/
