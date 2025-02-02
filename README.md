# TOPSIS Method for Selecting the Best Pretrained Model for Text Conversational

## Overview
This project implements the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to evaluate and rank pretrained models for text conversation based on multiple performance criteria.

## 1. Models and Evaluation Criteria
The following pretrained models are evaluated:
- **ChatGPT**
- **Claude**
- **Gemini**
- **Mistral**
- **LLaMA**

The criteria for evaluation include:
- **Dialog Quality (DQ)** (Higher is better)
- **Engagement Score (ES)** (Higher is better)
- **Response Time (RT)** (Lower is better)
- **Memory Usage (MU)** (Lower is better)

### Decision Matrix
| Model   | Dialog Quality (DQ) | Engagement Score (ES) | Response Time (RT) | Memory Usage (MU) |
|---------|---------------------|---------------------|-----------------|-----------------|
| ChatGPT | 85                  | 0.92                | 1.2             | 9.0             |
| Claude  | 80                  | 0.88                | 1.5             | 10.0            |
| Gemini  | 78                  | 0.85                | 1.1             | 8.0             |
| Mistral | 82                  | 0.90                | 1.3             | 9.5             |
| LLaMA   | 79                  | 0.86                | 1.4             | 9.2             |


## 2. Implementation Steps
The **TOPSIS method** is applied using the following steps:
1. **Normalization** of the decision matrix.
2. **Weighted normalization** of the decision matrix.
3. **Calculation of ideal best and worst solutions**.
4. **Distance computation** from the ideal solutions.
5. **Calculation of TOPSIS scores** for each model.
6. **Ranking of models** based on the scores.

## 3. Code Execution
The implementation is provided in the Jupyter Notebook: `102203584_Trish_Rustagi_Topsis_For_Pretrained_Models.ipynb`.

## 4. Results
### Final Rankings:
![image](https://github.com/user-attachments/assets/896d251c-47eb-4ceb-867c-5a81c8ccec67)


### TOPSIS Output:
![image](https://github.com/user-attachments/assets/1698dbaf-8c50-4273-a20b-9c55ef9aa08a)


## 5. Usage
1. Clone this repository.
2. Run `102203584_Trish_Rustagi_Topsis_For_Pretrained_Models.ipynb` in Jupyter Notebook.
3. Modify the dataset to evaluate different models.

## 6. Conclusion
Using the **TOPSIS method**, we effectively ranked pretrained models for text conversation based on multiple criteria, providing a systematic approach for model selection.
