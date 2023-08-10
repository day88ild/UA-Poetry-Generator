# Poetry Generation with TensorFlow

This project explores the use of deep learning techniques to generate poetry written by Ukrainian writers. The goal is to train a model that can create new poetic verses in the style of these authors.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project leverages TensorFlow and deep learning techniques to generate poetry in the style of Ukrainian poets. It utilizes a recurrent neural network (RNN) with GRU layers to learn the patterns and structures present in the provided poems. The trained model is then used to generate new verses.

## Dataset

The project uses a dataset of poems written by prominent Ukrainian poets. The dataset includes both the titles and the text of the poems. You can also find it on Kaggle (https://www.kaggle.com/datasets/oleksiykh/taras-shevchenko-poetry).

## Data Preprocessing

The poems are preprocessed to remove unnecessary characters, tokenize the text, and create sequences for training. The dataset is split into training and validation sets on training.

## Model Architecture

The model have simple architecture, that consists of an GRU-based recurrent neural network. The GRU layers capture the sequential patterns in the poetry and learn to generate new sequences of words.

## Training

The model is trained using the preprocessed dataset. The training process involves minimizing the sparse categorical cross-entropy loss.

## Results

The generated poetry showcases the model's ability to capture the style and themes of the original Ukrainian poets. While the generated verses may not always match human-written poetry, they provide a fascinating exploration of machine creativity. We managed to recreate Taras Shevchenko`s poems.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests for enhancements or bug fixes.
