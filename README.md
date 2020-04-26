# wordpress

```
# One time setup
$ mkdir wp-content
```

```
# Start wordpress and MySQL
$ docker-compose up

# Stop wordpress and MySQL
$ docker-compose down

# Check if containers are running properly
# This will show stopped containers also
$ docker ps -a
```

* Create your plugins in wp-content directory. It is mounted inside the container
