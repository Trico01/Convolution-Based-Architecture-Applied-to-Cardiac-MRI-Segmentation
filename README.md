# Machine-Learning-Deep-Learning-Final-Project
This is the final project of JHU EN.601.682 Machine Learning: Deep Learning course.

## Introduction
Improve efficiency and reliability in cardiac MRI segmentation by conducting a thorough comparison of the performance of various models.

## Methods
* Dataset: Automated Cardiac Diagnosis Challenge (ACDC) in MICCAI challenge.
* Setup: ConvDeconv, U-Net, and [GridNet](https://link.springer.com/chapter/10.1007/978-3-319-75541-0_8).
* Evaluation: Dice Score and Hausdorff Distance.

## Results
| Model      | LV (Dice)        | LV (HD)          | RV (Dice)        | RV (HD)          | MYO (Dice)       | MYO (HD)         |
|------------|------------------|------------------|------------------|------------------|------------------|------------------|
| ConvDeconv | 0.90 ± 0.020     | 7.15 ± 4.47      | 0.74 ± 0.0039    | 30.83 ± 10.84    | 30.83 ± 10.84    | 7.31 ± 4.46      |
| U-Net      | 0.92 ± 0.019     | 9.61 ± 5.83      | 0.78 ± 0.0038    | 25.50 ± 9.72     | 0.87 ± 0.012     | 6.07 ± 3.66      |
| GridNet    | 0.92 ± 0.018     | 6.86 ± 4.56      | 0.80 ± 0.0037    | 16.02 ± 7.24     | 0.87 ± 0.013     | 4.90 ± 2.63      |

![visualization](https://github.com/Trico01/Machine-Learning-Deep-Learning-Final-Project/visualization.jpg)
