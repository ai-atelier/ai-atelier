# Docker 

## Upgrading an image in DockerHub

Build the container:

```
docker build -t aiatelier:tf-1.8.0-gcloud-cpu .
```

Tag and push to Docker Hub:
```
DOCKERCLOUD_NAMESPACE=aiatelier docker tag aiatelier:tf-1.8.0-gcloud-cpu aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
DOCKERCLOUD_NAMESPACE=aiatelier docker push aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
```


## Using a pre-built image

Run:

```
docker run -p 0.0.0.0:6006:6006 -p 8888:8888 -it aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
```
Authenticate with google-cloud-sdk:
```
gcloud auth application-default login
```

Start Tensorboard:
```
tensorboard --logdir=.  # replace with the path to your tf summaries
```
