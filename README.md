# ai-atelier
AI Atelier notebooks, lessons, and tutorials

### Docker

Build the container:

```
docker build -t ai_atelier:tf-1.8.0-gcloud-cpu .
```

Tag and push to Docker Hub:
```
DOCKERCLOUD_NAMESPACE=aiatelier docker tag ai_atelier:tf-1.8.0-gcloud-cpu aiatelier/ai_atelier:tf-1.8.0-gcloud-cpu
DOCKERCLOUD_NAMESPACE=aiatelier docker push aiatelier/ai_atelier:tf-1.8.0-gcloud-cpu
```

Run:

```
docker run -p 0.0.0.0:6006:6006 -p 8888:8888 -it aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
```

Start Tensorboard:
```
gcloud auth application-default login
tensorboard --logdir=<your-gs-url>
```

