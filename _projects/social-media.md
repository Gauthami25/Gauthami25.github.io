---
title: "Image Captioning"
layout: single-portfolio
excerpt: "<img src='/images/projects/Image_Captioning.png' alt=''>"
collection: projects
order_number: 40
header: 
  og_image: "projects/Image_Captioning.png"
---


## Project Overview

📌 In this project, I took on the task of implementing an encoder-decoder image captioning system. This involved utilizing a pre-trained Convolutional Neural Network to encode the image, resulting in the production of a hidden state. This hidden state was then decoded using an LSTM to generate a descriptive caption.

📌 The highlight of this approach is in its ability to make captions more informative and context-aware. Traditional Recurrent Neural Networks (RNNs) possess a form of memory that facilitates contextual understanding. However, due to computational constraints, this memory is often restricted to just a few elements. To address this, I utilized the attention models to spotlight the most relevant elements within an input image.

📌 In practice, these systems find valuable applications in a range of fields. For instance, they are extensively used in computer vision tasks, enabling automated systems to provide detailed and contextually relevant descriptions of images or videos. Real life use cases include assisting visually impaired individuals by converting visual information into textual form. Additionally, in industries like e-commerce and social media, image captioning systems enhance content accessibility, user engagement, and search engine optimization. They also play a pivotal role in robotics and autonomous systems, enabling machines to understand and communicate information about their surroundings.

<!-- > A brief aside on Git-speak: these periodic indented blocks will explain the terminology that Git uses to help you underst what each Git comm actually does.


To save yourself some time  do this faster, simply press <kbd>Ctrl</kbd>+<kbd>c</kbd>.[^2] -->

![](/images/posts/creating-website/p4_i1.png)


[Link to project on Github](https://github.com/Gauthami25/Projects/tree/main/Image%20Caption%20Generator)

