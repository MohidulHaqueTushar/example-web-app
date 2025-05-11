# Web Application
A simple Flask web application, containerized using Docker for easy deployment. This project demonstrates how to build, run, and deploy a Python Flask app both locally and using Docker.


## Using Docker
You can run the application directly from the docker hub by using the following command:
```
docker pull haque313/example-web-app:latest
```

You can run it by using the following command, **ONLY** for the docker-desktop:

```
docker run -d -p 8000:8000 haque313/example-web-app:latest
```

## Access the App
- Visit: [http://localhost:8000](http://localhost:8000)
- Visit: [http://localhost:8000/how-are-you](http://localhost:8000/how-are-you)

## Build
you can also build the image again by using the [Dockerfile](https://github.com/MohidulHaqueTushar/example-web-app/blob/main/Dockerfile.txt) and [app.py](https://github.com/MohidulHaqueTushar/example-web-app/blob/main/app.py) from this github repository.