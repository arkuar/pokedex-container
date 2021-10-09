# Dockerised pokedex

The container exposes port 5000 where the app is running so you need to publish a port to be able to connect to the container

To run the container, run the following command
```bash
$ docker run pokedex -p 5000:5000
```
For detached version
```bash
$ docker run pokedex -dp 5000:5000
```

The app should now be running in http://localhost:5000

## Heroku link
https://arkuar-pokedex-pipeline.herokuapp.com/
