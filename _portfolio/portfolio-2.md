---
title: "Style Transfer for Professional Photographic Edits"
excerpt: "<br/><img src='/images/HDRnet_prediction.png'>"
collection: 
---
This project is an extension of my computer vision class project. For the original project, I had to read, summarize, and present a modern computer vision paper; I chose to do this on [Deep Bilateral Learning for Real-Time Image Enhancement](https://groups.csail.mit.edu/graphics/hdrnet/data/hdrnet.pdf). Roughly speaking, this paper summarized a neural network architecture that is able to learn black-box style transfers. In particular, one of the datasets used in the paper was the MIT-Adobe 5k dataset, a dataset with 5000 images, each image edited by five different photographers.

I decided to see if I could replicate on professional photographic edits that were actually delivered to customers. My friend [Justin Ho](https://weddingsbyjustin.com/) is a professional photographer with a distinctive style. Overall, the model performed well, but the predictions are noticably off. In addition, some of the predictions had strange color tints, that definitely looked strange. I'm currently exploring further work, where I'm going to adjust some parts of the model, training process (pretraining and then finetuning), and data collection - even though there were 3000 photos, they were sourced from only five different photography shoots.

[My Github repo](https://github.com/alexwdong/hdrnet-pytorch)

Justin's edits vs Neural Nets (Justin wins)

<img src='/images/Justinho_edit.png'>  <img src='/images/HDRnet_prediction.png'>


