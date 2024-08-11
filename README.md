![Version](https://img.shields.io/badge/version-1.1.0-blue.svg) ![License](https://img.shields.io/badge/license-CC%20BY%204.0-green.svg)

# Open-Source Datasets

Welcome to the Vector Database Cloud Open-Source Datasets repository! This repository serves as a curated collection of datasets that are useful for training and evaluating vector database applications. Here, you can find a variety of datasets along with the necessary metadata and usage guidelines.


## Table of Contents

1. [About](#about)
2. [Prerequisites](#prerequisites)
3. [Datasets](#datasets)
    1. [Text Datasets](#text-datasets)
    2. [Image Datasets](#image-datasets)
    3. [Audio Datasets](#audio-datasets)
    4. [Multimodal Datasets](#multimodal-datasets)
4. [Usage](#usage)
5. [Contribution and Feedback](#contribution-and-feedback)
6. [Code of Conduct](#code-of-conduct)
7. [License](#license)
8. [Disclaimer](#disclaimer)


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


## License

This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

Copyright (c) 2024 Vector Database Cloud

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- Attribution — You must give appropriate credit to Vector Database Cloud, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests Vector Database Cloud endorses you or your use.

Additionally, we require that any use of this guide includes visible attribution to Vector Database Cloud. This attribution should be in the form of "Dataets curated by Vector Database Cloud" or "Based on Vector Database Cloud Datasets", along with a link to https://vectordbcloud.com, in any public-facing applications, documentation, or redistributions of this guide.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For the full license text, visit: https://creativecommons.org/licenses/by/4.0/legalcode


## Disclaimer

The information and resources provided in this community repository are for general informational purposes only. While we strive to keep the information up-to-date and correct, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability or availability with respect to the information, products, services, or related graphics contained in this repository for any purpose. Any reliance you place on such information is therefore strictly at your own risk.

Vector Database Cloud configurations may vary, and it's essential to consult the official documentation before implementing any solutions or suggestions found in this community repository. Always follow best practices for security and performance when working with databases and cloud services.

The content in this repository may change without notice. Users are responsible for ensuring they are using the most current version of any information or code provided.

This disclaimer applies to Vector Database Cloud, its contributors, and any third parties involved in creating, producing, or delivering the content in this repository.

The use of any information or code in this repository may carry inherent risks, including but not limited to data loss, system failures, or security vulnerabilities. Users should thoroughly test and validate any implementations in a safe environment before deploying to production systems.

For complex implementations or critical systems, we strongly recommend seeking advice from qualified professionals or consulting services.

By using this repository, you acknowledge and agree to this disclaimer. If you do not agree with any part of this disclaimer, please do not use the information or resources provided in this repository.
