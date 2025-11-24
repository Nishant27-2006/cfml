
# Computational Solutions for Cardiovascular Diagnostics  
![knockout_logo](https://github.com/Nishant27-2006/georgia-tech/blob/main/gtcfml.png)

# ECG Analysis with Hybrid CNN-SVM

_All research and materials produced during tenure as Research Lead at Georgia Tech's Cardiovascular Fluid Mechanics Laboratory. The code, data, and insights are property of Georgia Tech and collaborators involved in the project._

## Overview

I led this research at Georgia Tech to tackle a massive issue: heart disease. Despite medical advances, it kills too many people. We focused on early detection using non-invasive ECG analysis.

This project details the machine learning system I built to diagnose heart disease. We used data from PhysioNet and created a pipeline that merges **convolutional neural networks (CNNs)** with **support vector machines (SVMs)**. The goal was to maximize accuracy while keeping the system practical for real doctors.

## What We Built

We developed a hybrid CNN-SVM model to get the best of both worlds.

- **The Approach:** We used CNNs for automatic feature extraction and SVMs for classification.
- **The Features:** The model looks at temporal data like QRS-duration and RR intervals. It also analyzes frequency-domain features using Fast Fourier Transform (FFT).
- **The Logic:** The CNN component automatically pulls relevant signal features. This helps the system scale across different datasets without manual tweaking.

## The Results

The model hit **100% classification accuracy** on our training and validation sets. While those numbers are strong, they point to overfitting. The system is highly accurate on data it knows but needs adjustment to handle unseen test data effectively.

## My Role

As Research Lead, I managed the project from the initial idea to the final code.

- I designed the ML pipeline and led the feature extraction work.
- I managed a team of research assistants to refine the algorithms.
- I worked directly with clinicians to ensure our code addressed actual medical needs.
- We published our findings in the _Journal of Computational Biology_ and presented at the Georgia Tech Biomedical Symposium.

## What Is Next

The current results prove that hybrid models work for ECG analysis, but there is room to improve.

- **Fixing Overfitting:** I plan to use cross-validation and data augmentation to help the model generalize. I will also test L2 regularization and dropout techniques.
- **Clinical Use:** The long-term plan is to get this into live clinical workflows so doctors can make faster diagnoses.
- **Validation:** We need to test this on a larger patient group to prove it works in the real world.

## Publications

- **Machine Learning for Cardiovascular Diagnostics**, _Journal of Computational Biology_, 2024.
- **Integrating AI into Clinical Workflows**, _Georgia Tech Biomedical Symposium_, 2024.

---
*Special thanks to the Wallace H. Coulter Department of Biomedical Engineering, Georgia Tech, and all collaborating clinicians.*

![Wallace H. Coulter BME Building](https://github.com/Nishant27-2006/georgia-tech/blob/main/gtcfml.png)

---

## Contact Information
For further inquiries or collaboration opportunities, please feel free to reach out via my GitHub profile or email me at **nishantg2706@gmail.com**.

---
