# Skin lesion images classification
* This repo was run on colab notebook.
* Build a custom dataset and custom model to classify 7 classes of skin lesion images from [ISIC challenge 2018 task3 dataset](https://challenge.isic-archive.com/data/#2018)
* Try to use multiple backbones and evaluate their performace.
* Training phase was in 25 epochs, learning rate 0.001 and using SGD with momentum optimizer for all backbone.

## ResNet101:
*	Validate accuracy reached its peak at 0.8187 in 6th epoch.
*	Prediction for test dataset hit 0.7321 accurate while its macro f1 score was 0.5445.

## VGG19:
*	Validate accuracy reached its peak at 0.7357 in 12th epoch.
*	Prediction for test dataset hit 0.6905 accurate while its macro f1 score was 0.3993.

## ResNet50:
*	Validate accuracy reached its peak at 0.8238 in 22th epoch.
*	Prediction for test dataset hit 0.7540 accurate while its macro f1 score was 0.5529.

## ResNet152:
*	Validate accuracy reached its peak at 0.8342 in 2th epoch.
*	Prediction for test dataset hit 0.7539 accurate while its macro f1 score was 0.5529.
