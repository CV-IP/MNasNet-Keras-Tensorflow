# MNasNet
[Keras (Tensorflow) Implementation](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/Mnasnet.py) of MNasNet and an example for training and evaluating it on the MNIST dataset. 
Check also the [eager execution implementation](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/MnasnetEager.py)

According to the paper: [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/pdf/1807.11626.pdf)

## Requirement
* Python 2.7+
* Tensorflow-gpu 1.10

## Train it
Train the [MNasNet model](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/Mnasnet.py) on the MNIST dataset! just execute:
```
python train.py
```
For checking and inspecting the Mnasnet model described in the paper, execute:
```
python Mnasnet.py
```



## Train it with eager execution
Train the [MNasNet (eager) model](https://github.com/Shathe/MNasNet-Keras-Tensorflow/blob/master/MnasnetEager.py) on the MNIST dataset! just execute:

```
python train_eager.py
```

The eager execution implementation also outputs logs on Tensorboard. For its visualization:
```
tensorboard --logdir=train_log:./logs/train, test_log:./logs/test
```

## MnasNet for... Semantic Segmentation!
In this other repository, [FC-Mnasnet](https://github.com/Shathe/Semantic-Segmentation-Tensorflow-Eager) I added a decoder to the MnasNet architecture in order to turn it into a semantic segmentation model.



![alt text](https://github.com/Shathe/MNasNet-Keras-Tensorflow/raw/master/mnasnet.png)
