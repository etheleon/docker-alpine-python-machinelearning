
Python Machine Learning tools Docker image
==========================================

This image is based on
[Alpine Linux Python 3.5 image](https://hub.docker.com/r/etheleon/alpine-python3/),
which is only a 60MB image, and contains popular Machine Leaning tools:

* numpy
* pandas
* scipy
* scikit-learn

Download size of this image is only:



Usage Example
-------------

```bash
$ docker run --rm etheleon/alpine-python-machinelearning python3 -c 'import numpy; print(numpy.arange(3))'
```

Once you have run this command you will get printed `array([0, 1, 2])` from Python!
