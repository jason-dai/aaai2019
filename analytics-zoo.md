# Analytics Zoo
*A unified analytics + AI platform for __distribtued TensoFlow, Keras and BigDL on Apache Spark__*

---

## What is Analytics Zoo?

__Analytics Zoo__ provides a unified analytics + AI platform that seamlessly unites *__Spark, TensorFlow, Keras and BigDL__* programs into an integrated pipeline; the entire pipeline can then transparently scale out to a large Hadoop/Spark cluster for distributed training or inference. 

To make it easy to build and productionize deep learning applications for Big Data, Analytics Zoo also provides a rich set of analytics and AI support for the end-to-end pipeline (e.g., easy-to-use abstractions and APIs, common feature engineering operations, built-in deep learning models, reference use cases, etc.).

- [High level pipeline APIs](#high-level-pipeline-apis)
  - [`nnframes`](#nnframes): native deep learning support in *Spark DataFrames and ML Pipelines*
  - [`autograd`](#autograd): build custom layer/loss using *auto differentiation operations* 
  - [Transfer learning](#transfer-learning): customize pretained model for *feature extraction or fine-tuning*
  - [Model serving](#model-serving): productionize *model serving and inference* using [POJO](https://en.wikipedia.org/wiki/Plain_old_Java_object) APIs
  
- [Built-in deep learning models](#built-in-deep-learning-models)
  - [Object detection API](#object-detection-api): high-level API and pretrained models (e.g., SSD and Faster-RCNN) for *object detection*
  - [Image classification API](#image-classification-api): high-level API and pretrained models (e.g., VGG, Inception, ResNet, MobileNet, etc.) for *image classification*
  - [Text classification API](#text-classification-api): high-level API and pre-defined models (using CNN, LSTM, etc.) for *text classification*
  - [Recommedation API](#recommendation-api): high-level API and pre-defined models (e.g., Neural Collaborative Filtering, Wide and Deep Learning, etc.) for *recommendation*
  
- [Reference use cases](#reference-use-cases): a collection of end-to-end *reference use cases* (e.g., anomaly detection, sentiment analysis, fraud detection, image augmentation, object detection, variational autoencoder, etc.)

## How to use Analytics Zoo?
- To get started, please refer to the [Python install guide](https://analytics-zoo.github.io/master/#PythonUserGuide/install/) or [Scala install guide](https://analytics-zoo.github.io/master/#ScalaUserGuide/install/).

- For more information, You may refer to the [Analytis Zoo document website](https://analytics-zoo.github.io/)

- For additional questions and discussions, you can join the [Google User Group](https://groups.google.com/forum/#!forum/bigdl-user-group) (or subscribe to the [Mail List](mailto:bigdl-user-group+subscribe@googlegroups.com)) 

---
