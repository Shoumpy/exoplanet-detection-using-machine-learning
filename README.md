## *Exoplanet Detection System using Machine Learning*

This repository contains the code and resources for an Exoplanet Detection System using Machine Learning. The goal of this project is to detect exoplanets, which are planets that orbit stars outside our solar system, using machine learning techniques. The system takes in astronomical data, such as light curves or spectra, and uses various machine learning algorithms to classify the data into different categories, such as exoplanet candidates or false positives.

## *Overview*
1. The data directory contains the datasets used in this project, which include light curves and spectra data obtained from telescopes.
2. The preprocessing directory contains scripts and notebooks for preprocessing the raw data, including cleaning, normalization, and feature extraction.
3. The models directory contains implementations of machine learning models used for exoplanet detection, such as support vector machines (SVM), random forests, and deep learning models.
4. The evaluation directory contains scripts and notebooks for evaluating the performance of the models, including metrics such as accuracy, precision, recall, and F1 score.
5. The results directory contains the results obtained from the trained models, including classification reports, confusion matrices, and visualization of the detected exoplanets.
6. The demo directory contains a demo script or notebook that showcases how to use the trained model on new data for exoplanet detection.

## *Requirements*

1. Python 3.7 or above
2. Libraries: numpy, pandas, scikit-learn, matplotlib, tensorflow (for deep learning models)

## *Usage*

1. Clone the repository and navigate to the project directory.
2. Install the required libraries using pip or conda by running pip install -r requirements.txt.
3. Preprocess the data by running the scripts/notebooks in the preprocessing directory.
4. Train the machine learning models using the scripts/notebooks in the models directory.
5. Evaluate the performance of the trained models using the scripts/notebooks in the evaluation directory.
6. Use the trained model on new data for exoplanet detection by running the demo script/notebook in the demo directory.

## *Results*

The trained models achieved an accuracy of over 90% in detecting exoplanets from the given datasets. The performance of the models was evaluated using various metrics, such as accuracy, precision, recall, and F1 score, and the results are provided in the results directory.

## *Citation*

If you use this Exoplanet Detection System in your research or project, please cite this repository as follows:

@misc{exoplanet_detection_ml, <br>
  author = {Your Name}, <br>
  title = {Exoplanet Detection System using Machine Learning}, <br>
  year = {2023}, <br>
  publisher = {GitHub}, <br>
  journal = {GitHub repository}, <br>
  howpublished = {\url{https://github.com/your_username/exoplanet_detection_ml}}, <br>
}

## *License*
This project is released under the **MIT License**. Feel free to use, modify, and distribute the code for academic or commercial purposes. However, please note that the results obtained from this project are not guaranteed to be accurate and should be used at your own discretion.
