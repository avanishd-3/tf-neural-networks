# tf-neural-nets
Collection of neural netwworks made with TensorFlow and Keras.

Each network also includes the model weights in a .keras file.


## Usage Instructions

```
git clone https://github.com/avanishd-3/tf-neural-networks.git
```

Then run the notebooks

Models can also be loaded with

```
model = tf.keras.models.load_model("model_filename.keras")
```

## ANNs

There are 3 models here.

1. Classification model based on the Fashion MNIST dataset (~89% accuracy).
2. Regression model based on the Auto MPG dataset
3. High-accuracy classification model based on the MNIST dataset (~97% accuracy).
4. Classification model based on the CIFAR-10 dataset (~49% accuracy, which is pretty high for a non-CNN model on an image-recognition dataset)

## CNNs

There is 1 model here.

1. Classification model based on the Fashion MNIST dataset (~91.5% accuracy).
2. Transfer learning (based on Xception) binary classification model trained on TensorFlow cat or dog dataset.
    - No weight for this one, because it is exceeds the GitHub file size.
    - Training is pretty quick, though, because most of the training has already been done.
