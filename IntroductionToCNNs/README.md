## Introduction To Convolutional Neural Networks (CNNs) 

The aim of this project is to provide a an introduction to the deep learning algorithms for computer vision tasks. In particular, an introduction to deep learning frameworks such as Tensorflow and Keras are provided through a set of jupyter notebooks. The MNIST dataset is used as an example for classification tasks.

### Setup

1. Create (and activate) a new environment with Python 3.6.
** Linux or Mac: **

```bash
conda create --name cvdl python=3.6
source activate cvdl
```

2. Clone the repository and navigate to root of the repo. Then install several dependencies.

```bash
git clone https://github.com/n-lamprou/ComputerVisionWithDL.git
cd ComputerVisionWithDL
pip install .
```

3. For using jupyter notebooks, create an IPython kernel for the cvdl environment.

```bash
python -m ipykernel install --user --name cvdl --display-name "cvdl"
```

### Notebooks 

The following notebooks can be found. It is recommended to follow in order as they progressively build up knowledge and aim to show the benefits of using CNNs for computer vision tasks.

* IntroductionToTensorflow-Basiscs
* IntroductionToTensorflow-SimpleLogisticClassifier
* IntroductionToTensorflow-DeepNeuralNetwork
* ConvolutionalNeuralNetworksWithKeras 
