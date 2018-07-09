# pytorch-siamese

This is a port of [pytorch-siamese](https://github.com/delijati/pytorch-siamese)

thanks [Josip Delic](https://github.com/delijati) for releasing his code
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

![](https://github.com/smallflyingpig/pytorch_siamese_mnist/blob/master/result.png)

