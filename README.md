# ai-atelier
AI Atelier notebooks, lessons, and tutorials

## Notebooks

### Section 1

[Tensors ops and variables](https://colab.research.google.com/drive/1XBJlKVNMbE6DDIvOVxJCiXweegcpZNeT)

[Training and optimization](https://colab.research.google.com/drive/1fH0qKc8XSplWqHYtrFSc5X-QICGngjYD)

[Layers and optimizers](https://colab.research.google.com/drive/1JJ5ySzzPsAXSa0NZcMawiQtCQRXtjnaw)

[Classification](https://colab.research.google.com/drive/1pvELXxNeqiw4pROK5werrnUHl5s3fHS4)

### Section 2

[Datasets API and the Quickdraw Dataset](https://colab.research.google.com/drive/1cOneywoRDY7ezPQ7FsN8QROLc-iVkXT-)

[Tensorboard and Checkpoints](https://colab.research.google.com/drive/1htd7yqRcfWAcRs6GuSqfDuhL1Brk_qXS)

[Convolution and Pooling](https://colab.research.google.com/drive/17nXAIytqSUCw0bn1Sdj2nF0TBMFRMwPo)

[Convolutional Networks](https://colab.research.google.com/drive/1G-s3zdFsOCTC2Xap0zHPM8YtVOOtZ68f)

[Diving deeper into CNNs](https://colab.research.google.com/drive/1u_fZ2xVpcpu6azXZjeWs8oaxHdF9L6Z6#scrollTo=KgOu27PJXsu3)


## Docker installation

Run:
```
docker run -p 0.0.0.0:6006:6006 -p 8888:8888 -it aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
```

Start Tensorboard:
```
tensorboard --logdir=.  # replace with the path to your tf summaries
```
