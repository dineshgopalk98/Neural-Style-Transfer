# Neural-Style-Transfer

## Abstract

This repository focuses on adapting a neural style transfer model based on existing papers. The model learns style from style images and content from content images to create a new image combining both. Training utilises the pre-trained VGG19 network for feature extraction from different layers. The project explores the model's behaviour with various parameters and layer selections, aiming for faster training and optimal results in the future.

## I. Introduction

Neural Style Transfer involves guiding a network to replicate desired features in a target image. Gram matrix and feature correlations in a CNN are employed to create style-based images. High-level features contribute to content, extracted through different CNN layers. The total loss, a weighted sum of content and style losses, is optimised to generate the desired target image.

## II. Related Work

Inspired by works like "A Neural Algorithm for Artistic Style" by Gatys et al [3], and "Preserving Color in Neural Artistic Style Transfer" by Gatys et al [4], the project explores different experiments and evaluation methods in neural style transfer models.

## III. Methodology

Utilizing inspirations from various papers, the VGG-19 pretrained network processes content and style images. Features are extracted for selected layers, and Gram matrices are created for style loss layers. Max pooling is replaced with average pooling for improved results. Extensive experimentation involves different optimizers and style loss layer variations. Color restoration is added for preserving content image colors.

## IV. Results

Experiments include using style loss from a single layer, observing intricate patterns from different layers. The interplay between style and content features is explored, allowing for a nuanced understanding of layer effects. The relative weight between style and content layers can be adjusted. The repository demonstrates results with various content and style image combinations, emphasizing the impact of layer choices on the final output.

Code Disclaimers:

1. Clone the repository.
2. Install required dependencies.
3. Explore Jupyter notebooks for detailed experiments.
4. Experiment with different content and style images.
5. Adjust parameters and layers for personalised results.

**Dependencies:** Python, TensorFlow, Keras, OpenCV
