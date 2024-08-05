# Skin Cancer Detection with 3D TBP

This repository contains the implementation of various machine learning and deep learning techniques for the detection of skin cancer using 3D Total Body Photography (TBP). The project leverages multiple data modalities and architectures to enhance the detection accuracy and robustness.

## Overview

Skin cancer detection is a critical area in medical research. This project aims to develop an efficient and accurate detection system using state-of-the-art techniques. The implemented models include Convolutional Neural Networks (CNNs), Deep Neural Networks (DNNs), Recurrent Neural Networks (RNNs), and a variety of machine learning algorithms such as Bayes, AdaBoost, Gradient Boosting Regressor (GBR), Random Forest (RF), Balanced Random Forest (BRF), and CatBoost.

## Special Thanks to Collaborators

tysm [Noman Jaffer](mailto:nomanjaffar517@gmail.com) (Drop a follow on his [Linkedin](https://www.linkedin.com/in/noman-jaffar-823543254/))


## Architectures and Modalities

Four different modalities were used for development, each implemented in separate Jupyter notebooks. Below are the architectural images corresponding to each modality:

1. **Dual-Head Architecture Detection**
   ![Dual-Head-Architecture-Detection](https://github.com/ahmedembeddedxx/skin-cancer-detection-with-3D-TBP/blob/main/architectures/Dual-Head-Architecture-Detection.png)

2. **Image Modality Detection**
   ![Image-Modality-Detection](https://github.com/ahmedembeddedxx/skin-cancer-detection-with-3D-TBP/blob/main/architectures/Image-Modality-Detection.png)

3. **Multi-Modality Detection**
   ![Multi-Modality-Detection](https://github.com/ahmedembeddedxx/skin-cancer-detection-with-3D-TBP/blob/main/architectures/Multi-Modality-Detection.png)

4. **Text Modality Detection**
   ![Text-Modality-Detection](https://github.com/ahmedembeddedxx/skin-cancer-detection-with-3D-TBP/blob/main/architectures/Text-Modality-Detection.png)

## Implementation Details

- **Notebooks**: The development was carried out using Kaggle notebooks, each dedicated to one of the modalities mentioned above.
- **Models and Algorithms**: The project employs a variety of models and algorithms:
  - CNNs
  - DNNs
  - RNNs
  - Bayes
  - AdaBoost
  - GBR (Gradient Boosting Regressor)
  - RF (Random Forest)
  - BRF (Balanced Random Forest)
  - CatBoost

## Data Source

The data used in this project is sourced from the ISIC (International Skin Imaging Collaboration) and is licensed under GNU. The dataset includes a wide variety of skin images that are essential for training and evaluating the models.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Kaggle API (for downloading the dataset)
- Necessary Python libraries (listed in `requirements.txt`)

### Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/ahmedembeddedxx/skin-cancer-detection-with-3D-TBP.git
   cd skin-cancer-detection-with-3D-TBP
   ```

2. Install the required Python libraries:
   ```sh
   pip install -r requirements.txt
   ```

3. Download the dataset from ISIC using Kaggle API:
   ```sh
   kaggle datasets download -d <isic-competetions-2024 dataset>
   ```

4. Unzip the downloaded dataset and place it in the appropriate directory as specified in the notebooks.

### Usage

Open the Jupyter notebooks corresponding to the modality you wish to explore and run the cells to train and evaluate the models.

## Results

The results of the different models and modalities are documented within the notebooks. Comparative analysis and performance metrics such as accuracy, precision, recall, and F1-score are provided to highlight the efficacy of each approach.

## Contributions

Contributions to enhance the project are welcome. Please fork the repository and create a pull request with detailed changes.

## License

This dataset is licensed under the GNU License, and notebooks under MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- ISIC for providing the dataset.
- Kaggle for the computational resources.
- Open-source contributors and developers for the libraries and tools used in this project.
