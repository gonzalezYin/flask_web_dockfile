# flask_web_dockfile
A very simple dockfile to implement a flask-based web.

```docker build --no-cache -t 'jy/simple_flask_web' .```

```docker run -d --name flask_web_1 -p 90:8080 jy/simple_flask_web```

```docker ps```

```docker exec -it jy/simple_flask_web bash```

```docker restart jy/simple_flask_web```
