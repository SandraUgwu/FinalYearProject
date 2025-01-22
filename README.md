# Investigating Gender Bias in Machine Learning Models for Image Classification

This repository contains the analysis and report for my final year project, exploring how machine learning models handle gender bias in image datasets. Using the FairFace dataset, this research evaluates bias and accuracy across CNN, RF, SVM, DT, and LR models under various conditions.

## Project Description

The project investigates the effectiveness of machine learning models in managing gender bias in image classification tasks. Key aspects include:
- Creation of biased datasets with varying male-to-female ratios and sizes.
- Evaluation of model performance (accuracy, precision) and bias (statistical parity difference).
- Hyperparameter tuning to enhance fairness and accuracy.

## Dataset and Files

- **FairFace Dataset**: A diverse image dataset for bias measurement. [FairFace GitHub](https://github.com/joojs/fairface)
- **Data organization (Dissertation).ipynb**: Notebook for organizing and processing the FairFace dataset.
- **Final Copy (Dissertation).ipynb**: Final project analysis and evaluation notebook.
- **Result Visualization (Dissertation).ipynb**: Notebook for visualizing model results and bias metrics.
- **annotated-Final Report (Dissertation).pdf**: Full report detailing methodology, results, and conclusions.

## Tasks and Analysis

1. **Dataset Preparation**: Organized images into categories for gender classification.
2. **Bias Subsets**: Created subsets with imbalanced male-to-female ratios.
3. **Model Training**: Trained CNN, RF, SVM, DT, and LR models on biased datasets.
4. **Bias Evaluation**: Measured bias using statistical parity difference (SPD).
5. **Visualization**: Generated visual reports on accuracy, bias, and precision.

## Technologies Used

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn, TensorFlow, AIF360

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FinalYearProject.git
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn sklearn tensorflow aif360
3. Download the FairFace dataset and place it in the data/ folder
4. Run the notebooks in the following order:
   - Data organization (Dissertation).ipynb
   - Final Copy (Dissertation).ipynb
   - Result Visualization (Dissertation).ipynb
  
## Results Summary
    - CNN achieved the highest accuracy (91%) but amplified bias in imbalanced datasets.
    - RF was the most balanced model, achieving 90% accuracy with minimal bias.
    - SVM reduced bias significantly but suffered from low accuracy (54%).
    - DT exhibited high bias and low accuracy in most scenarios.
    
## Acknowledgments
This project was completed as part of my MSc in Artificial Intelligence and Data Science at the University of Hull.
