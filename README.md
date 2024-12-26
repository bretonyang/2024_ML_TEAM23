# Pitch Type Prediction Using RNN

Welcome! This is the repository for Group 23's project 🦍, _Pitch Type Prediction Using RNN_. Here, you'll find everything you need to reproduce our results and explore our approach to predicting MLB pitch types using recurrent neural networks.

---

## Steps to Use the Notebook

1. Open the `notebook.ipynb` file in Google Colab.
2. Follow the instructions in the "1 Project Setup" section to:
   - Install necessary libraries
   - Import dependencies
   - Download the dataset for the project
3. Once the setup is complete, run the cells in the notebook sequentially from top to bottom to reproduce our results.

#### Customizing the Dataset

By default, our code downloads pitching data for Hunter Greene during the 2024 season. If you'd like to explore data for a different pitcher or time range, you can easily modify the configuration. For example, to download Shota Imanaga's pitching data for the 2024 season, use the following settings:

```py
### CONFIG ###
input_last_name = "Imanaga"
input_first_name = "Shota"
input_start_date = '2024-04-01'
input_end_date = '2024-11-02'
output_root = 'input_all_data_2024.csv'
### CONFIG ###
```

#### Example Dataset

To get a sense of what the downloaded CSV files should look like, check out the Example Dataset folder. It contains sample data for Mason Miller and Shota Imanaga's 2024 pitching performances.

#### Need Help?

If you have any questions or run into issues, feel free to reach out via email: breton0429@gmail.com

---

## What Else is in the Repo

Here's a quick overview of other folders in this repository:

- `Meeting Minutes`: Includes all nine meeting minutes reports from the semester.
- `Proposal`: Contains our proposal video, peer reviews of other teams' proposals, and our responses to feedback.
- `Video & Presentation`: Includes our project video slides, the final video, questions from other teams, and slides used during the presentation Q&A session.

## Project Report

The complete report, titled **"RNN-Based Pitch Type Prediction: Insights into Sequential Patterns and Strategy Refinement"**, is available in this repository. It details the methodology, experiments, and results of this project. You can find it here: [RNN_Based_Pitch_Type_Prediction_Report.pdf](link/to/report).

Highlights from the report include:
- Accuracy improvement from 55% (Bayesian baseline) to 69% using RNN models.
- Techniques for handling imbalanced pitch type distributions with a generalist-specialist voting mechanism.
- Model comparisons between Simple RNN, LSTM, and Attention-based LSTM.

For more details, please refer to the PDF.