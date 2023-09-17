# DeepWeeds CNN

Repository containing CNN models for detection and classification of the DeepWeeds dataset. Part of a team project for Machine Learning (CS3244) course taken in AY 2022/23 Sem 1.

## Background

Our team (of 5 members) was tasked with choosing a dataset from a given list and frame a motivated problem statement around that dataset. We are then intended to spend the next 10 weeks exploring the problem using various machine learning techniques. As part of this project, I took upon the task of exploring the problem using Convolutional Neural Networks (CNN).

You can additionally checkout the [project proposal](/resources/Project%20Proposal.pdf) and [final presentation](/resources/Final%20Presentation.pptx)

## Dataset

- [Github Repo](https://github.com/AlexOlsen/DeepWeeds)
- [Kaggle](https://www.kaggle.com/datasets/imsparsh/deepweeds)
- [Know Your Data TFDS](https://knowyourdata-tfds.withgoogle.com/#tab=STATS&dataset=deep_weeds)

> The DeepWeeds dataset consists of 17,509 unique 256x256 colour images in 9 classes. There are 15,007 training images and 2,501 test images. These images were collected in situ from eight rangeland environments across northern Australia.

## Repository contents

- /src - Jupyter notebooks for the CNN models and final ensemble
- /models - corresponding models weights
- /resources - proposal, presentation, and model structures
- /final_images - 1:8:1 split
  - /test
  - /train
  - /validation - labelled directories
    - /chinese_apple
      - images.txt - list of image filenames from this labelled split
    - /lantana
    - /negative

## Team

- Bryan Tee Pak Hong
- Cheong Yee Ming
- Cheah Yan (Xie Yan)
- Kong Fanji
- Yeluri Ketan
