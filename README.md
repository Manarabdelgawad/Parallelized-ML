# Parallelized-ML
This project implements a machine learning pipeline for lung cancer prediction using parallel and distributed processing techniques.

The goal is to efficiently preprocess data, perform feature selection, 

and train classification models (SVM and Random Forest) by utilizing threading and multiprocessing.

Threading: For data loading and preprocessing (lightweight tasks).

Multiprocessing: For CPU-intensive tasks like feature selection and model training.

Shared Memory: To allow processes to share data without duplicating it.

Queue: For inter-process communication to exchange data/results.

Process Pool: To parallelize model training efficiently.
