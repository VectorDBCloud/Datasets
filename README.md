![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

# Open-Source Datasets

Welcome to the Vector Database Cloud Open-Source Datasets repository! This repository serves as a curated collection of datasets that are useful for training and evaluating vector database applications. Here, you can find a variety of datasets along with the necessary metadata and usage guidelines.

## Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Datasets](#datasets)
  - [Text Datasets](#text-datasets)
  - [Image Datasets](#image-datasets)
  - [Audio Datasets](#audio-datasets)
  - [Multimodal Datasets](#multimodal-datasets)
- [Usage](#usage)
- [Contribution and Feedback](#contribution-and-feedback)
- [Code of Conduct](#code-of-conduct)
- [Disclaimer](#disclaimer)


## About

This repository collects open-source datasets suitable for vector database applications. Each dataset is accompanied by metadata, usage instructions, and any necessary preprocessing scripts.

## Prerequisites

- Sufficient storage space for downloading datasets
- Appropriate software for handling specific dataset formats (e.g., Python with pandas for CSV files)


## Datasets

### Text Datasets

- **[Common Crawl](https://commoncrawl.org/)**  
  *Description*: A massive dataset containing web crawl data, useful for training large-scale language models and other NLP tasks.  
  *License*: CC BY 4.0

- **[Wikipedia Dump](https://dumps.wikimedia.org/)**  
  *Description*: Periodically updated dumps of Wikipedia's content, widely used for language modeling, information retrieval, and more.  
  *License*: CC BY-SA 3.0

- **[IMDB Reviews](https://ai.stanford.edu/~amaas/data/sentiment/)**  
  *Description*: A dataset of movie reviews used for sentiment analysis and other text classification tasks.  
  *License*: No formal license; free for academic use.

### Image Datasets

- **[ImageNet](http://www.image-net.org/)**  
  *Description*: A large-scale image dataset organized according to the WordNet hierarchy, widely used for image classification tasks.  
  *License*: Custom; non-commercial research only.

- **[COCO (Common Objects in Context)](https://cocodataset.org/)**  
  *Description*: A dataset for object detection, segmentation, and captioning, containing images of complex everyday scenes.  
  *License*: CC BY 4.0

- **[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)**  
  *Description*: A dataset consisting of 60,000 32x32 color images in 10 different classes.  
  *License*: MIT

### Audio Datasets

- **[LibriSpeech](https://www.openslr.org/12/)**  
  *Description*: A corpus of approximately 1,000 hours of read English speech, suitable for training and evaluating ASR systems.  
  *License*: CC BY 4.0

- **[VoxCeleb](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)**  
  *Description*: A large-scale speaker recognition dataset containing speech from celebrities across the world.  
  *License*: CC BY 4.0

### Multimodal Datasets

- **[MS COCO Captions](https://cocodataset.org/#captions-2015)**  
  *Description*: An extension of the COCO dataset, containing images with associated captions, useful for image-captioning tasks.  
  *License*: CC BY 4.0

- **[Flickr30k](http://shannon.cs.illinois.edu/DenotationGraph/)**  
  *Description*: A dataset of 30,000 images with captions, designed for image captioning and multimodal research.  
  *License*: Custom; non-commercial research only.

## Usage

To use these datasets:

1. Navigate to the specific dataset you're interested in.
2. Follow the download instructions provided in the dataset's README.
3. Use the preprocessing scripts (if any) to prepare the data for your vector database.

## Contribution and Feedback

We encourage contributions from the community! If you have a dataset to share or suggestions for improvement, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Add your dataset or make your changes. Include comprehensive metadata, usage instructions, and any necessary preprocessing scripts.
4. Submit a pull request with a clear description of your contribution.

Please ensure datasets are properly licensed and attributed, and provide clear documentation for any preprocessing steps.

For any issues or suggestions, please use the issue tracker.


## Code of Conduct

We adhere to the [Vector Database Cloud Code of Conduct](https://github.com/VectorDBCloud/Community/blob/main/CODE_OF_CONDUCT.md). Please ensure contributions align with our community standards.


## Disclaimer

The datasets provided in this repository are collected from various sources and are subject to their respective licenses. While we strive to ensure all datasets are properly licensed for redistribution, users are responsible for verifying the license terms and using the datasets in compliance with those terms.

Vector Database Cloud is not responsible for the content of the datasets or any consequences resulting from their use. Always verify the suitability of a dataset for your specific use case before using it in any production environment.
