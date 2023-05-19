# InceptionNet-Variations
This GitHub repository aims to provide comprehensive overview of the evolution of GoogLeNet, a popular Convolutional Neural Network architecture developed by Researchers at Google for image classification tasks. The repository will showcase the different iterations of the GoogLeNet architecture, from the first paper Szegedy et al. in 2015, which introduced the Inception module, to the later versions of the model proposed by Szegedy et al. in 2016 and 2017. Each iteration of the model is implemented using popular deep learning frameworks such as TensorFlow and PyTorch, and is trained and evaluated on standard images classification datasets such as CIFAR-10 and ImageNet. The repository provides code and documentation for each implementation, making it valuable resource for researchers and practitioners interested in the history and development of the GoogLeNet architecture.

__They include the following__: 

* [Add a batch normalization layer](https://arxiv.org/abs/1502.03167)
* [Make adjustments to the Inception block (width, choice and order of convolutions)](https://arxiv.org/abs/1512.00567)
* [Use label smoothing for model regularization](https://arxiv.org/abs/1512.00567)
* [Make further adjustments to the Inception block by adding residual connection](https://arxiv.org/abs/1602.07261)


## Citations

```bibtex
@misc{ioffe2015batch,
      title={Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift}, 
      author={Sergey Ioffe and Christian Szegedy},
      year={2015},
      eprint={1502.03167},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

```bibtex
@misc{szegedy2015rethinking,
      title={Rethinking the Inception Architecture for Computer Vision}, 
      author={Christian Szegedy and Vincent Vanhoucke and Sergey Ioffe and Jonathon Shlens and Zbigniew Wojna},
      year={2015},
      eprint={1512.00567},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

```bibtex
@misc{szegedy2016inceptionv4,
      title={Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning}, 
      author={Christian Szegedy and Sergey Ioffe and Vincent Vanhoucke and Alex Alemi},
      year={2016},
      eprint={1602.07261},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
