## PyTorch Tutorial

### Stanford CS230 
- [PyTorch code example](https://cs230.stanford.edu/blog/pytorch/)

### Deep Learning Zero To All
- [모두를 위한 DL in PyTorch](https://github.com/deeplearningzerotoall/PyTorch)
- [PyTorchZeroToAll Youtube Lists](https://www.youtube.com/playlist?list=PLlMkM4tgfjnJ3I-dbhO9JTw7gNty6o_2m&disable_polymer=true)
- [The Lab Slides](https://deeplearningzerotoall.github.io/season2/lec_pytorch.html)

### Datacamp Course 1551 PyTorch Tutorials
 - [Introduction to PyTorch](https://s3.amazonaws.com/assets.datacamp.com/production/course_15510/slides/chapter1.pdf)
 - [Activation Functions](https://s3.amazonaws.com/assets.datacamp.com/production/course_15510/slides/chapter2.pdf)
 - [Convolution Operator](https://s3.amazonaws.com/assets.datacamp.com/production/course_15510/slides/chapter3.pdf)
 - [The Sequential Module](https://s3.amazonaws.com/assets.datacamp.com/production/course_15510/slides/chapter4.pdf)

### Understanding PyTorch with an example
- [A step-by-step tutorial](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e#dc96)
- [Automatic differentiation in PyTorch](https://openreview.net/pdf/25b8eee6c373d48b84e5e9c6e10e7cbbbce4ac73.pdf)

## Incredible PyTorch
- [PyTorch List for each Applications](https://github.com/ritchieng/the-incredible-pytorch)

## Deep Learning Book (MIT)
- [Deep Learing Reference Book](http://www.deeplearningbook.org/)

## Pytorch Fundamentals

### Core Traning Step

```python
output_batch = model(train_batch)
loss = loss_fn(output_batch, labels_batch)

optimizer.zero_grad()   # clear previous gradients
loss.backward()         # compute gradients of all variables wrt loss

optimizer.step()        # perform updates using calculated gradients
```

### AUTOGRAD : 자동 미분
- [PyTorch Tutorial Site](https://tutorials.pytorch.kr/beginner/blitz/autograd_tutorial.html#sphx-glr-beginner-blitz-autograd-tutorial-py)

### PyTorch GPU
- [PyTorch on the GPU - Training Neural Networks with CUDA](https://www.youtube.com/watch?v=Bs1mdHZiAS8)


### Activation Functions
- [Empirical Evaluation of Rectified Activations in Convolution Network](https://arxiv.org/pdf/1505.00853.pdf)
- [nn module activation](https://github.com/pytorch/pytorch/blob/master/torch/nn/modules/activation.py)

### Data loader and Loss Function
 - [PyTorch Loss Functions Basics](https://towardsdatascience.com/pytorch-basics-intro-to-dataloaders-and-loss-functions-868e86450047)

### 자주 쓰는 Loss Function
- [Cross Entropy vs MSE ](https://nuguziii.github.io/dev/dev-002/)

### Binary Cross Entropy
- [Simple Neural Network with BCELoss](https://medium.com/analytics-vidhya/simple-neural-network-with-bceloss-for-binary-classification-for-a-custom-dataset-8d5c69ffffee)

### CrossEntropy vs BCELoss 함수 사용 시 주의점
 - [BCELoss vs Cross Entropy in PyTorch](https://jaeyung1001.tistory.com/45)

### Quasi-Hyperbolic Momentum and ADAM for Deep Learning
 - [ QHM, QHAdam paper](https://arxiv.org/pdf/1810.06801.pdf) 

### PyTorch LSTM
 - [PyTorch LSTM](https://www.deeplearningwizard.com/deep_learning/practical_pytorch/pytorch_lstm_neuralnetwork/)


### Batch Normalization
- [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167.pdf)

### How to Develop DL Models 
- [PyTorch Tutorial](https://machinelearningmastery.com/pytorch-tutorial-develop-deep-learning-models/)

### Distributed Paraellel PyTorch 
- [Distributed Parallel Library](https://www.kaggle.com/residentmario/notes-on-pytorch-library-features/code)


## PyTorch 101

- [PyTorch 101, Part1 : Understanding Graphs, Automatic Differentiation and Autograd ](https://blog.paperspace.com/pytorch-101-understanding-graphs-and-automatic-differentiation/)
- [PyTorch 101, Part 2: Build your first Nueral Network](https://blog.paperspace.com/pytorch-101-building-neural-networks/)
- [PyTorch 101, Part 3: Going Deep with PyTorch](https://blog.paperspace.com/pytorch-101-advanced/)
- [PyTorch 101, Part 4: Memory Management and Using Multiple GPUs](https://blog.paperspace.com/pytorch-memory-multi-gpu-debugging/)
- [PyTorch 101, Part 5: Understanding Hooks](https://blog.paperspace.com/pytorch-hooks-gradient-clipping-debugging/)


## PyTorch Examples

### Image Classification
- [Image Classification with PyTorch](https://www.pluralsight.com/guides/image-classification-with-pytorch)

### Geodata Machine Learning
- [Geospatial data workshop](https://www.kaggle.com/jcarrillo/machine-learning-for-geospatial-data-workshop-2a)

### NLP BERT 
- [BERT fine tunning for PyTorch](https://medium.com/@aniruddha.choudhury94/part-2-bert-fine-tuning-tutorial-with-pytorch-for-text-classification-on-the-corpus-of-linguistic-18057ce330e1)

