# ai-atelier
AI Atelier notebooks, lessons, and tutorials

### Tensors and training
https://colab.research.google.com/drive/1giICtOP1QN7INJzNiAKg73vcRDJydTWr

### Training as optimization

https://colab.research.google.com/drive/1fH0qKc8XSplWqHYtrFSc5X-QICGngjYD

### Dense layers & Optimizers

https://colab.research.google.com/drive/1kdcaObMwZ_Gb7UvRzjlV634sI9ILznLq

### Classification

https://colab.research.google.com/drive/1pvELXxNeqiw4pROK5werrnUHl5s3fHS4

### Docker 

Build the container:

```
docker build -t aiatelier:tf-1.8.0-gcloud-cpu .
```

Tag and push to Docker Hub:
```
DOCKERCLOUD_NAMESPACE=aiatelier docker tag aiatelier:tf-1.8.0-gcloud-cpu aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
DOCKERCLOUD_NAMESPACE=aiatelier docker push aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
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

