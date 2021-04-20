# Dataset-Distillation

Approach:

We use [dataset-distillation](https://github.com/SsnL/dataset-distillation) to generate 10 MNIST one-shot image samples, and save the image-labels in a [pickle](./image_data.pkl) file. We then use Tensorflow-Keras to train a model using the synthetic images, and evaluate the performace using the MNIST testing dataset.

However, we only get around 10-30% accuracy when training using the 10 synthetic distilled images.  
