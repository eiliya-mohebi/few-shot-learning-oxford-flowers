# Few-Shot Learning on Oxford Flowers

This repository contains a project on few-shot learning using the Oxford Flowers 102 dataset. The project demonstrates how to download and prepare the dataset, generate few-shot learning episodes, and build/train both Siamese (contrastive) and Triplet networks using TensorFlow and Keras.

## Overview

- **Dataset Preparation:** Downloads the Oxford Flowers 102 dataset, extracts images, and organizes them by class.
- **Data Processing:** Loads images, resizes them, and normalizes pixel values.
- **Episode Generation:** Implements functions to create few-shot learning episodes.
- **Embedding Model:** Uses a pre-trained ResNet50 (with frozen weights) as the backbone and adds additional layers to produce a 128-dimensional embedding.
- **Siamese Network:** Builds and trains a Siamese network with contrastive loss.
- **Triplet Network:** Builds and trains a triplet network with a custom triplet loss.

## Getting Started

### Prerequisites

- Python 3.8 or above
- TensorFlow (tested with TensorFlow 2.x)
- Other dependencies as listed in the `requirements.txt`.
