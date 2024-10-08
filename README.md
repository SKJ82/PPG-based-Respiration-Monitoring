# PPG-based-Respiration-Monitoring

This project focuses on developing a Cycle Generative Adversarial Network (CycleGAN) model to estimate respiratory rate accurately from photoplethysmography (PPG) signals. The model achieved a Mean Absolute Error (MAE) of 0.22, demonstrating its effectiveness in predicting respiratory rates.

Key Features:
Model Architecture: Utilized a CycleGAN, an advanced deep learning architecture, to handle the complex mapping between PPG signals and respiratory rates.

Data Preprocessing:

Normalization: Applied normalization to scale the PPG and respiratory signals for stable model training.
Downsampling: Reduced the sampling rate of the PPG signals to optimize computational efficiency without losing critical information.
Window Extraction: Divided the continuous signals into time windows, allowing the model to focus on relevant sections of data for better performance.
Cross-Validation: Implemented 5-fold cross-validation to ensure the model's reliability and generalizability across different patient groups. This approach provides a robust evaluation by training and validating the model on multiple subsets of data.

Performance:
Achieved a Mean Absolute Error (MAE) of 0.22, reflecting the model’s high accuracy in estimating respiratory rates from PPG signals.
