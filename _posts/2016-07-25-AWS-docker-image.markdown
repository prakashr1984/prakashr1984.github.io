---
published: true
title: AWS docker image
layout: post
tags: [deeplearning, AWS, docker]
---

## My Deep Learning AWS docker image

An Nvidia docker image for quick and easy deep learning setup (with GPU) in AWS or any other compute platform.
The docker image contains the following . Full source can be found [here](https://github.com/prakashr1984/docker/tree/master/datascience)

* Cuda 7.5
* CuDNN 5.0
* Anaconda 2.7
* Theano
* Lasagne

*Please follow the tutorial [here](https://prakashr1984.github.io/notes/deep-learning-with-AWS) for more details*

---

### Image

Docker image is hosted [here](https://hub.docker.com/r/prakashr1984/datascience/)

---

### Usage

    nvidia-docker run -p 8888:8888 -it prakashr1984/datascience jupyter notebook

---
