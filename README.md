# ai-atelier
AI Atelier notebooks, lessons, and tutorials

## Notebooks

### Tensors and training
https://colab.research.google.com/drive/1giICtOP1QN7INJzNiAKg73vcRDJydTWr

### Training as optimization

https://colab.research.google.com/drive/1fH0qKc8XSplWqHYtrFSc5X-QICGngjYD

### Dense layers & Optimizers

https://colab.research.google.com/drive/1kdcaObMwZ_Gb7UvRzjlV634sI9ILznLq

### Classification

https://colab.research.google.com/drive/1pvELXxNeqiw4pROK5werrnUHl5s3fHS4

### Deeper networks

https://colab.research.google.com/drive/1s7Z1g5fcYOhlQiVUPPWFe6PooeMaQHaj

### Shapes

https://colab.research.google.com/drive/1uC6-WaOwP7DcgiFX1PUcl0u2hr_MPElh

## Docker installation

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
