---
layout: post
title: "Softwares for Microscopy Images"
author: "Qiqi Lu"
category: blog
date: 2024-07-09
---

### napari
[Napari](https://napari.org/stable/index.html) is a `Python` library for n-dimensional image visualisation, annotation, and analysis. 

[Napari plugins](https://napari.org/stable/plugins/building_a_plugin/first_plugin.html#what-is-a-plugin) are just `Python` packages.

#### napari-imagej
[napari-imagej](https://napari.imagej.net/en/latest/) is a layer on top of `PyImageJ` (i.e., a napari plug-in), automating data conversions and enabling access to `ImageJ` funcitonality within one unified napari interface.

Operation systems: `Linux`, `macOS`, `Windows`

### deepImageJ
[DeepImageJ](https://deepimagej.github.io/) is a user-friendly plugin that enables the use of a variety of pre-trained neural networks in `ImageJ` and `Fiji`.

It gives access to the largest bioimage repository of pre-trained deep learning models (`BioImage Model Zoo`)

### BioImage.IO
[BioImage.IO](https://bioimage.io/#/) or BioImage Model Zoo is an repository for sharing AI models, datasets and tools for bioimage analysis.

### CSBDeep
[CSBDeep](https://csbdeep.bioimagecomputing.com/) is a deep learning toolbox for microscopy image restoration and analysis.

### ZS-DeconvNet Fiji plugin
[ZS-DeconvNet Fiji plugin](https://tristazeng.github.io/ZS-DeconvNet-page/Tutorial/#Fiji%20plugin) is a `Java`-based plugin for ZS-DeconvNet, which enables one-click training and inference of ZS-DeconvNet.

The ZS-DeconvNet Fiji plugin was developed based on [TensorFlow-Java 1.15.0](https://www.tensorflow.org/jvm?hl=zh-cn), which is compatible with CUDA version of 10.1 and cuDNN version of 7.5.1.

For the model developed using `Pytorch` and `Java`, [DeepJavaLibrary](https://www.tensorflow.org/jvm?hl=zh-cn) may be a choice.

### PyImageJ
[PyImageJ](https://py.imagej.net/en/latest/index.html) is a robust solution for `Python`-based `ImageJ` access, including its data structures and plug-ins.

PyImageJ is a libaray for programmers, requiresing expplicit conversion of Python data structures such as Numpy images into equicalent Java before they can be passed to ImageJ routines.

### ZeroCostDL4Mic
[ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) is a toolbox for the training and implementation of common Deep Learning approaches to microscopy imaging and a collection of self-explanatory `Jupyter Notebooks` for Google Colab.. It exploits the ease of use and access to GPU provided by Google Colab.

### DL4MicEverywhere
[DL4MicEverywhere](https://henriqueslab.org/pages/dl4miceverywhere) is an open-source platform that aims to make deep learning more accessible for bioimage analysis. It builds on the previous `ZeroCostDL4Mic` platform and advances it further to allow more flexible training and deployment of deep learning models across diverse computational environments.

### ImJoy
[ImJoy](https://imjoy.io/#/)'s core is a severless pregressive web application offering a fast and reliable user experience across all mainstream platforms, including laptops and mobile devices.

ImJoy’s functionalities are provided by independently operating plugins (written in different languages) that can be organized into workflows.

### ilastik
[ilastik](https://www.ilastik.org/) is an interactive learning and segmentation toolkit.

### Icy
[Icy](https://icy.bioimageanalysis.org/) is an open community platform for bioimage informatics.

Language: `Java`

### NIH Image
[NIH Image](https://imagej.net/software/nih-image) is the precursor to ImageJ.

### ImageJ
[ImageJ](https://imagej.net/software/imagej/) is public domain software for processing and analyzing scientific images, with many derivatives and variants, including `ImageJ2`, `Fiji`, and others.

Language: `Java`

### ImageJ2
[ImageJ2](https://imagej.net/software/imagej2/) is a rewrite of `ImageJ` for multidimensional image data, with a focus on scientific imaging.

Language: `Java`

### Fiji
[Fiji](https://imagej.net/software/fiji/) is an image processing package—a “batteries-included” distribution of `ImageJ2`, bundling a lot of plugins which facilitate scientific image analysis.

Language: `Java`

### BioImageXD
[BioImageXD](https://www.bioimagexd.net/) is a free open source software package for analyzing, processing and visualizing multi-dimensional microscopy images.

Language: `C++` or `Python`

### CellProfiler
[CellProfiler](https://cellprofiler.org/) is a  free open-source cell image analysis software designed to enable biologists without training in computer vision or programming to quantitatively measure phenotypes from thousands of images automatically. 

Language: `Python`

### QuPath
[QuPath](https://qupath.github.io/) is an open source software for bioimage analysis and can be esily integration with other tools, including ImageJ.

Language: `Java`

### KNIME
[KNIME](https://www.knime.com/) offers a complete platform for end-to-end data science, from creating analytic models, to deploying them and sharing insights within the organization, through to data apps and services.

### StarDist
[StarDist](https://github.com/stardist/stardist) is an Python implementation of star-convex object detection for 2D and 3D images.

Language: `Python`

### BiaPy
[BiaPy](https://github.com/BiaPyX/BiaPy) is an open source Python library that provides deep-learning workflows for a large variety of bioimage analysis tasks, including 2D and 3D semantic sgmentation, instance segmentation , object detection, image denoising, single image super-resolution, self-supervised learning, image classification and image to image translation.

### BioImage Suite
[BioImage Suite](http://bioimagesuite.com/) is a web-based medical image analysis software with image processing, image registration and visulization capabilities.

### Vaa3D
[Vaa3D](https://home.penglab.com/proj/vaa3d/home/index.html) (3D visualization-assisted analysis) is an open-source software suite for multi-dimensional data visualization and analysis.

### VisBio
[VisBio](https://loci.wisc.edu/visbio/) is a biological visualization tool designed for easy visualization and analysis of multidimensional image data. It displays data with `VisAD` and is bundled with `ImageJ`.

Language: `Java`

### VisAD
[VisAD](https://visad.ssec.wisc.edu/) is a Java component library for interactive and collaborative visualization and analysis of numerical data.
