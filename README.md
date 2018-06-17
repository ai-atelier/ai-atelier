# ai-atelier
AI Atelier notebooks, lessons, and tutorials

## Notebooks

### Section 1

[Tensors ops and variables](https://colab.research.google.com/drive/1XBJlKVNMbE6DDIvOVxJCiXweegcpZNeT)

[Training and optimization](https://colab.research.google.com/drive/1fH0qKc8XSplWqHYtrFSc5X-QICGngjYD)

[Layers and optimizers](https://colab.research.google.com/drive/1JJ5ySzzPsAXSa0NZcMawiQtCQRXtjnaw)

[Classification](https://colab.research.google.com/drive/1pvELXxNeqiw4pROK5werrnUHl5s3fHS4)

[Deeper Models](https://colab.research.google.com/drive/1ghkjgO-Sf6jx3Y3BarnvHPAuGO1yIpkb)

[Shapes](https://colab.research.google.com/drive/1uC6-WaOwP7DcgiFX1PUcl0u2hr_MPElh)

### Section 2

[Datasets API in Depth](https://drive.google.com/open?id=1cOneywoRDY7ezPQ7FsN8QROLc-iVkXT-)

[Datasets, Tensorboard, and Checkpoints](https://colab.research.google.com/drive/1IZbY4PE_qpaMBqfXLBRSguSa4F3E7gW5)

[Convolution and Pooling](https://colab.research.google.com/drive/17nXAIytqSUCw0bn1Sdj2nF0TBMFRMwPo)

[Convolutional Networks](https://colab.research.google.com/drive/1G-s3zdFsOCTC2Xap0zHPM8YtVOOtZ68f)

[Regularization and Data Augmentation](https://drive.google.com/open?id=1u_fZ2xVpcpu6azXZjeWs8oaxHdF9L6Z6)


## Docker installation

Run:
```
mkdir ~/summaries
docker run -p 0.0.0.0:6006:6006 -p 8888:8888 -v ~/summaries:/root/summaries -it aiatelier/aiatelier:tf-1.8.0-gcloud-cpu
```

Start Tensorboard:
```
tensorboard --logdir=summaries
```
