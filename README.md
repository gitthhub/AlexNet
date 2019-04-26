### README
Using tensorflow-keras to reproduce AlexNet.

Load pre-trained weights.

Benchmark model on ILSVRC-2012 validation dataset.

```
Using 1 crop per image when testing (compare to 5 crops)
Top-1 error rate: 0.480 (compare to 0.407 in paper)
Top-5 error rate: 0.241 (compare to 0.182 in paper)
```

### Reference
[AlexNet Architecture](http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/myalexnet_forward_newtf.py)

[AlexNet Weights](http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/)

[ILSVRC Preprocess](http://calebrob.com/ml/imagenet/ilsvrc2012/2018/10/22/imagenet-benchmarking.html)
