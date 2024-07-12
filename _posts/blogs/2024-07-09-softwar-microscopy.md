---
layout: post
title: "Softwares for microscopy"
author: "Qiqi Lu"
category: blog
date: 2024-07-09
---

### napari
[Napari](https://napari.org/stable/index.html) is a Python library for n-dimensional image visualisation, annotation, and analysis. 

[Napari plugins](https://napari.org/stable/plugins/building_a_plugin/first_plugin.html#what-is-a-plugin) are just Python packages.

#### napari-imagej
[napari-imagej](https://napari.imagej.net/en/latest/) is a layer on top of PyImageJ (i.e., a napari plug-in), automating data conversions and enabling access to ImageJ funcitonality within one unified napari interface.

Operation systems: `Linux`, `macOS`, `Windows`

### deepImageJ
[DeepImageJ](https://deepimagej.github.io/) is a user-friendly plugin that enables the use of a variety of pre-trained neural networks in ImageJ and Fiji.

### CSBDeep
[CSBDeep](https://csbdeep.bioimagecomputing.com/) is a deep learning toolbox for microscopy image restoration and analysis.

### ZS-DeconvNet Fiji plugin
[ZS-DeconvNet Fiji plugin](https://tristazeng.github.io/ZS-DeconvNet-page/Tutorial/#Fiji%20plugin) is a `Java`-based plugin for ZS-DeconvNet, which enables one-click training and inference of ZS-DeconvNet.

The ZS-DeconvNet Fiji plugin was developed based on [TensorFlow-Java 1.15.0](https://www.tensorflow.org/jvm?hl=zh-cn), which is compatible with CUDA version of 10.1 and cuDNN version of 7.5.1.

For the model developed using `Pytorch` and `Java`, [DeepJavaLibrary](https://www.tensorflow.org/jvm?hl=zh-cn) may be a choice.

### PyImageJ project
[PyImageJ](https://py.imagej.net/en/latest/index.html) is a robust solution for `Python`-based `ImageJ` access, including its data structures and plug-ins.

PyImageJ is a libaray for programmers, requiresing expplicit conversion of Python data structures such as Numpy images into equicalent Java before they can be passed to ImageJ routines.

