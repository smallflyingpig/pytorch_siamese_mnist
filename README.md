# pytorch-siamese

This is a port of [pytorch-siamese](https://github.com/delijati/pytorch-siamese)

## Install
The project is based on python 3

This installation requires `cuda`,`pytorch` to be installed. 


## Run

```
$ python train_mnist.py --epoch 10
```

This dumps for every epoch ther current `state` and creates a `result.png`.

### Run specific model

```
$ python train_mnist.py -m model-epoch-7.pth
```

## Result

![](https://raw.githubusercontent.com/delijati/pytorch-siamese/master/result.png)

