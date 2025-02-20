---
title: "Yang's AiLearn Lab - Research"
layout: textlay
excerpt: "Yang's AiLearn Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

At AiLearn Lab, our mission is to demystify artificial intelligence and bridge the gap between academic research and industrial application. We are committed to advancing the understanding and implementation of AI technologies across various domains. Our collaborations with industry partners are designed to apply cutting-edge AI research to real-world challenges, creating innovative solutions that propel both scientific and practical advancements. By integrating academic insights with industry expertise, we aim to foster transformative technologies that can scale from the lab to the field, enhancing both economic and societal well-being.

---
## **On going research program**

**Overview:**

Our primary work focuses on utilizing new algorithms to train neural networks. Over the past decade, we have successfully employed non-iterative learning methods to train hundreds of feedforward neural networks, thousands to tens of thousands of autoencoders, and deep convolutional neural networks with up to 50 million parameters. For instance, our latest theory enabled us to successfully train a 101-layer ResNet using our novel learning methods, enhancing learning effectiveness and generalization performance.
![]({{ site.url }}{{ site.baseurl }}/images/projects/pami.jpg){: style="width: 80%; float: center; margin: 0px"}

**Method:**

We utilize Moore-Penrose matrix inversion to train all neurons in neural networks. As a result, we had to redesign the entire error backpropagation process and the parameter update mechanisms for each neuron layer. We also developed specific algorithms for different types of neural layers, including fully connected layers, ReLU layers, normalization layers, softmax layers, addition layers, and others.

**Result:**

Our method demonstrates that, with less than 50 million parameters, the proposed algorithm can significantly enhance performance and learning speed. Additionally, at the same performance level, the new training method can substantially reduce the number of parameters in the neural network. This leads to more efficient models that require less computational resources.
**Future Direction:**

In the future, we aim to apply this method to train large language models (LLMs) such as BERT, GPT, and Llama. By leveraging our novel training algorithms, we hope to improve the efficiency and performance of these models. This could lead to faster training times, reduced computational costs, and enhanced generalization capabilities in natural language processing tasks.


