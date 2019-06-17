# Car Recognition

## Dependencies
All dependencies are already installed in CoLab. If you want to run notebook on your local system, you need to install these dependencies first. 

- [fastai](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [PyTorch](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Scikitlearn](https://keras.io/#installation)
- [Pandas](https://keras.io/#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

## Usage

### Train

Run train.ipynb on Google Colab by clicking the badge. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nithiroj/car-recognition/blob/master/train.ipynb)

#### Validation acc:
**88.70%**

### Test

Run test.ipynb on Google Colab by clicking the badge. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nithiroj/car-recognition/blob/master/test.ipynb)

#### Test acc:
**88.88%**

### Demo
Run train.ipynb on Google Colab by clicking the badge. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nithiroj/car-recognition/blob/master/demo.ipynb)


### Application
Download [pre-trained model](https://github.com/foamliu/Car-Recognition/releases/download/v1.0/model.96-0.89.hdf5) into "model" folder then run:

```bash
$ python demo.py --i [image_path]
```

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nithiroj/car-recognition/blob/master/Car_Recognition.ipynb)

This repo contains codes and materials for [Facial Keypoints Detection with PyTorch](https://medium.com/diving-in-deep/facial-keypoints-detection-with-pytorch-86bac79141e4) article. You can open the notebook in Colab by clicking the badge above.
