# Dataset-Distillation

Approach:

We use [dataset-distillation](https://github.com/SsnL/dataset-distillation) to generate 10 MNIST one-shot image samples, and save the image-labels in this [pickle](./image_data.pkl) file. We then use Tensorflow-Keras to train a model using the synthetic images, and evaluate the performace using the MNIST testing dataset.

Traing for 50 epochs with a batch size of 10, we get an average of around 34 ± 13 % accuracy (avg of 50 runs) on the MNIST testing dataset. 
