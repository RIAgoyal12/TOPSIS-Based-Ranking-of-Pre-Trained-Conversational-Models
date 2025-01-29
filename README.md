## TOPSIS-Based-Ranking-of-Pre-Trained-Conversational-Models

# Overview

This project applies TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) to rank pre-trained models for text-based conversational AI. The models are evaluated based on multiple performance criteria, and the best model is determined using the TOPSIS method.

# Dataset

We consider the following five pre-trained models:

- *BERT*

- *GPT-3.5*

- *T5*

- *DialoGPT*

- *XLNet*

Each model is evaluated using five performance criteria:

1. Accuracy (Higher is better)

2. Perplexity (Lower is better)

3. Response Time (Lower is better)

4. BLEU Score (Higher is better)

5. F1 Score (Higher is better)
   
# Methodology

- Normalization: Performance values are normalized using Min-Max scaling.

- Weight Assignment: Each criterion is assigned a weight based on importance.

# TOPSIS Calculation:

- Compute the ideal best and ideal worst values.

- Calculate Euclidean distances from the best and worst values.

- Compute TOPSIS scores to determine rankings.

  # Installation & Usage

*Prerequisites*

Make sure you have Python installed along with the required libraries:

bash `` pip install numpy pandas matplotlib scikit-learn seaborn ``

# Results

The output will display a table ranking the models based on their TOPSIS scores.
Additionally, the script generates visualizations including:

- Bar Chart: Showing the TOPSIS scores of different models.

- Pie Chart: Displaying score distribution.

- Heatmap: Visualizing the weighted normalized decision matrix.

# Example Output
  ![image](https://github.com/user-attachments/assets/b8a32d3c-aa71-4041-8bf5-4fe4e7012829)

# Contribution

Feel free to contribute by adding new models, modifying criteria, or optimizing calculations!
