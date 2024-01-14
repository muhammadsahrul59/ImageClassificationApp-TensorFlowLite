# Image Classification App using TensorFlowLite ✨

## Project Description
Welcome to the Image Classification App using TensorFlowLite, where cutting-edge techniques and meticulous design come together to achieve exceptional model accuracy. This project leverages a dataset comprising more than 10,000 images, ensuring a diverse and extensive learning experience. The dataset has never been employed in any previous machine learning class submissions, guaranteeing novelty.

You can view the dataset in Kaggle :  [Animal -5 Mammal](https://www.kaggle.com/datasets/shiv28/animal-5-mammal?select=Animal)
## Key Features
- **Extensive Dataset**: The project utilizes a dataset exceeding 10,000 images, providing a rich source for training and testing the model.
- **Dataset Division**: The dataset is divided into an 80% training set and a 20% test set, ensuring a robust evaluation of the model's performance.
- **Sequential Model**: The model architecture follows a sequential design, facilitating a streamlined and intuitive structure.
- **Conv2D Maxpooling Layer**: Utilizing Conv2D and Maxpooling layers, the model captures hierarchical features for effective image classification.
- **Training Accuracy**: The model achieves training and validation set accuracies surpassing 92%, showcasing its capability to generalize well on unseen data.
- **Callback Implementation**: Employing callback techniques enhances the training process by allowing dynamic adjustments based on the model's performance.
- **Plotting Performance**: The project includes code for creating plots that visualize the model's accuracy and loss over the training epochs, aiding in performance analysis.
- **TF-Lite Model Export**: The model is saved in the TF-Lite format, ensuring compatibility for deployment on various platforms with resource constraints.

## Overview
This application is designed to classify mammalian animal objects (cats, dogs, lions, elephants, and horses) simply by photographing them using MobileNetV2 technology.

The model files are downloaded via Gradle scripts when you build and run the app. You don't need to do any steps to download TFLite models into the project explicitly. This sample demonstrates how to use TensorFlow Lite with Java.

This application should be run on a physical Android device.

![WhatsApp Image 2024-01-14 at 23 23 54_3e72a9b5](https://github.com/muhammadsahrul59/ImageClassificationApp-TensorFlowLite/assets/101655285/2f250f00-2cf4-40e9-85c5-f10b6ce2c184)

![lion_classification](https://github.com/muhammadsahrul59/ImageClassificationApp-TensorFlowLite/assets/101655285/62f21773-d1a3-4d1e-a661-27227bbe7e18)

![horse_classification](https://github.com/muhammadsahrul59/ImageClassificationApp-TensorFlowLite/assets/101655285/2ba0d742-8d7e-4ae0-9e23-5196912686c5)

![Screenshot 2024-01-14 232611](https://github.com/muhammadsahrul59/ImageClassificationApp-TensorFlowLite/assets/101655285/a32274a9-3b5f-42cc-b2ca-388965d47057)

## Build the demo using Android Studio

### Prerequisites

* The **[Android Studio](https://developer.android.com/studio/index.html)**
    IDE (Android Studio 2023.1.1 or newer). This sample has been tested on
    Android Studio Hedgehog

* A physical Android device with a minimum OS version of SDK 23 (Android 6.0 -
    Marshmallow) with developer mode enabled. The process of enabling developer
    mode may vary by device.

### Building

* Open Android Studio. From the Welcome screen, select Open an existing
    Android Studio project.

* From the Open File or Project window that appears, navigate to and select
    the ImageClassificationApp-TensorFlowLite/android directory.
    Click OK.

* If it asks you to do a Gradle Sync, click OK.

* With your Android device connected to your computer and developer mode
    enabled, click on the green Run arrow in Android Studio.

### Models used

Downloading, extraction, and placing the models into the assets folder is
managed automatically by the download.gradle file.

## Run the notebook only on Google Colab
```
- Download the file above
- open https://colab.research.google.com/
- Upload the file notebook.ipynb
```

or you can open it with this Google Colab Link below :

[![](https://img.shields.io/badge/Google%20colab-Open-FFC000.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAB8lBMVEUAAAD/7QL/6w7/6gz/6w3/6Qj/6Qj/6wj/6gf/6w//6w7/6xP/7gP/2hr/2xX/2jD/z0j/uHX/1zn/3Sz/3Sv/1zn/r4L/zE3/2jL/4ST/4Cf/0RP//zH/3S//2jL/2jL/2zH/3iv/3in/2zD/2jL/2jL/3C///0b/1B3/yxL/xAj/0SH/2DT/2TX/2TX/3C7/2jP/2DX/2DX/2DX/1zD/zRb/YwD/wgf/wQf/xAr/1iX/3C//3C//2zH/2Db/2jP/3C7/2zD/zBf/wgj/wgf/wgf/wQf/wQf/0ST/2y7/5B3/2TT/2TT/3iv/2y//zSD/wQb/wQf/wgf/wgf/wQf/wQf/zx7/3Cz/4x//2TT/2TX/4TD/zRb/wQf/wgf/wQf/wgf/wgf/wQf/wwr/1iT/3S//3C7/2zH/1zH/zBb/wQT/wgf/wQf/wQf/wgf//4r/xAj/0CD/2DT/2TX/2TX/3C7/zBb/wgj/wQf/wQf/wQf/wgf/xgf/0BL/6Rz/3C//2jL/2jP/2zH/3iz/vwD/wgf/wgf/wgf/wgf/xAf/wgf/2Rr/2hf/2TH/t3f//wD/1D//3S7/wgX/wAf/0wj/uQf/wQf/wwf/wgf/5gX/5h//6BT/5xb/6Q//6RD/xAf/xAf/xQf/xAf/xQf/xAf///9tAmifAAAApXRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAATiFmGgWFGaZi0EDAABa6v/5+32y//r/8WoBJ9viYD9wnv+kPlvc5TRg/XsAAArH4yEAAGz+cmL9dgAACsjhHgAAZ/50LOHcUzRbm/+VLUjT6TcAZvH89Pd5uv/x+fRxAgADRJSldRsYcKOVSAQAAAAAAAEAAAAAAQAAAAAAAAAAAAAAAAAAAABydb0CAAAAAWJLR0SlLrlKLwAAAAd0SU1FB+QIEQUaC7jgabcAAAABb3JOVAHPoneaAAAAwUlEQVQI12NgQAOMTMwsrGzsHJxc3DwMDLx8/AKCQsIiomLiEpJSDNIysnLyCopKyiqqauoaDJpa2jq6evoGhkbGJqZmDOYWllbWNrZ29g6OTs4uDK5u7h6eXt4+vn7+AYFBDMEhoWHhEZFR0TGxcfEJDIlJySmpaekZmVnZObl5DPkFhUXFJaVl5RWVVdU1DLV19Q2NTc0trW3tHZ1dDN09vX39EyZOmjxl6rTpMxgYZs6aPWfuvPkLFi5avATdAwCl1jTbaxUL4wAAAF5lWElmSUkqAAgAAAADABIBAwABAAAAAQAAADEBAgANAAAAMgAAAGmHBAABAAAAQAAAAAAAAABQaG90b3MgMi43LjAAAAIAAqAJAAEAAADTAAAAA6AJAAEAAADTAAAAAAAAAJOs9JgAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMTdUMDU6MjY6MTErMDA6MDBd4jn+AAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTE3VDA1OjI2OjExKzAwOjAwLL+BQgAAABh0RVh0ZXhpZjpFeGlmSW1hZ2VMZW5ndGgAMjExdjfLjwAAABd0RVh0ZXhpZjpFeGlmSW1hZ2VXaWR0aAAyMTHrqE6dAAAAEnRFWHRleGlmOkV4aWZPZmZzZXQANjTZeQZNAAAAGnRFWHRleGlmOlNvZnR3YXJlAFBob3RvcyAyLjcuMIcagsYAAAAASUVORK5CYII=)](https://colab.research.google.com/drive/1tCfvxL7WFj-_tchjhCCSTMAY3A7g64Nw?usp=sharing)
