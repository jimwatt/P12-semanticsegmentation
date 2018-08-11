# Semantic Segmentation

This project is in conjunction with the Udacity Self-Driving Car course.  In particular, the goal of this project is to implement a fully convolutional network to classify pixels in images of traffic scenes from the Kitti Road Dataset as either "road surface" or "not road surface".

* More detail about the approach is provided in [writeup.md](./writeup.md).

## Getting Started

### Prerequisites

```
Python 3
TensorFlow
Numpy
Scipy
Kitti Road Dataset
```

### Installing

1. Clone this project from GitHub:

```
git clone https://github.com/jimwatt/P12-semanticsegmentation.git
```

## Running the Code

* Run the `main.py` script to train the network, and perform inference on sample images: 

  ```
  python3 main.py
  ```

* The script will check that a GPU is available, and then begin training.  

* Results of inference on test images will be placed in a `runs` directory.

## Authors

* **James Watt**

<!--## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details-->

## Acknowledgments
This project is a submission to the Udacity Self-Driving Car nanodegree:

* `https://github.com/udacity/CarND-Semantic-Segmentation.git`

