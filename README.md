# MLA307 Sequence Models – Mini Project

**Course:** MLA307 – Sequence Models  
**Programme:** Year 3, Semester I  
**Assessment:** Mini Project (20%)  
**Project Type:** Business Intelligence Using Sequence Models

## 1. Project Overview

The purpose of this mini project is to identify a real-world Business Intelligence problem involving sequential or time-dependent data and develop a solution using a sequence model.

The project will demonstrate how sequential data can be collected, prepared, analysed, modelled, evaluated, and interpreted to support business decision-making.

Our group will select a suitable business problem, obtain an appropriate dataset, implement an RNN, LSTM, or GRU model, evaluate its performance, and provide practical business recommendations based on the findings.

## 2. Project Objectives

The main objectives are to:

- Identify and explain a real-world business problem.
- Collect or select an appropriate sequential dataset.
- Review existing research related to the chosen problem.
- Clean and prepare the dataset for modelling.
- Develop and train an appropriate sequence model.
- Evaluate the model using suitable performance metrics.
- Interpret the results from a business perspective.
- Provide practical recommendations based on the findings.

## 3. Possible Project Topics

The group may select one of the following topics:

### Topic 1: Customer Churn Prediction
Predict which customers are likely to stop using a company's services based on their historical behaviour or interactions.

### Topic 2: Time Series Forecasting
Predict future sales, demand, market trends, or resource utilisation using historical time-dependent data.

### Topic 3: Anomaly Detection
Identify unusual patterns in sequential data, such as fraudulent financial transactions, equipment failures, or unusual customer activities.

### Topic 4: Text Analysis and Sentiment Prediction
Analyse customer reviews or social media comments to predict positive, negative, or neutral sentiment.

### Topic 5: Recommendation System
Recommend products, services, or content based on customers' previous interactions and behaviour sequences.

**Selected project topic:** To be decided by the group.

## 4. Division of Work Among Four People

### Person 1: Problem Identification and Literature Review

**Main responsibility:** Research and report writing.

Tasks:
- Identify and explain the selected real-world business problem.
- Explain why the problem is important to businesses.
- Describe why sequential or time-dependent data is suitable for the problem.
- Identify the project aim, objectives, and research questions where appropriate.
- Find and review relevant research papers and previous studies.
- Explain existing methods and their limitations.
- Add proper in-text citations and references.

**Deliverables:**
- Introduction
- Business problem statement
- Project aim and objectives
- Literature review
- References and citations

### Person 2: Dataset Collection and Preparation

**Main responsibility:** Data collection, cleaning, and preprocessing.

Tasks:
- Find and download a suitable dataset.
- Record the dataset source, number of records, and relevant details.
- Explain the dataset features and target variable.
- Check for missing values, duplicate records, and incorrect data.
- Clean and prepare the dataset where necessary.
- Organise the data into a suitable sequential format.
- Split the data into training, validation, and test sets using an appropriate method.
- Document the preprocessing steps and decisions.

**Deliverables:**
- Original dataset
- Cleaned and prepared dataset
- Data preprocessing code
- Dataset description
- Explanation of data cleaning and preparation

### Person 3: Sequence Model Development

**Main responsibility:** Model selection, implementation, and training.

Tasks:
- Select a suitable RNN, LSTM, or GRU model.
- Explain why the selected model is appropriate for the project.
- Write the model development and training code.
- Train the model using the dataset prepared by Person 2.
- Adjust model settings where necessary.
- Save the trained model.
- Generate predictions using the trained model.
- Record training results, challenges, and solutions.

**Deliverables:**
- Model development and training code
- Saved trained model
- Prediction results
- Explanation of model selection
- Training results and challenges

### Person 4: Evaluation, Analysis, and Recommendations

**Main responsibility:** Model evaluation, business interpretation, and final report compilation.

Tasks:
- Evaluate the trained model using appropriate performance metrics.
- Prepare result tables and graphs.
- Generate a confusion matrix if appropriate for the task.
- Explain the model's performance and important sequential patterns.
- Identify the model's limitations.
- Explain how businesses could use the results.
- Provide practical recommendations.
- Write the conclusion.
- Combine all members' contributions into the final report.
- Check the final report for consistency, formatting, citations, and completeness.

**Deliverables:**
- Model evaluation results
- Tables and visualisations
- Performance analysis
- Business interpretation
- Limitations
- Recommendations and conclusion
- Compiled final report

## 5. Project Requirements

The completed project should include the following components:

1. Identification of a real-world business problem.
2. Collection or selection of an appropriate dataset.
3. Literature review of related research.
4. Selection and implementation of an RNN, LSTM, or GRU model.
5. Evaluation using suitable performance measures.
6. Analysis and interpretation of results from a business perspective.
7. Recommendations based on the findings.

## 6. Suggested Project Workflow

The group will follow these steps:

1. **Choose the topic:** Agree on one of the five suggested project areas.
2. **Define the problem:** Explain the business problem and project objectives.
3. **Collect the data:** Find a suitable dataset and document its source.
4. **Prepare the data:** Clean the dataset and organise it into sequential inputs.
5. **Develop the model:** Select and implement an appropriate sequence model.
6. **Train the model:** Train using the prepared training data.
7. **Evaluate the model:** Test the model using suitable performance metrics.
8. **Interpret the results:** Explain the findings and their business value.
9. **Make recommendations:** Suggest practical actions businesses can take.
10. **Prepare the final report:** Combine all sections and check the completed work.

## 7. Suggested Project Folder Structure

```text
MLA307-Sequence-Models/
│
├── README.md
│
├── data/
│   ├── original_dataset.csv
│   └── processed_dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   ├── train.py
│   └── evaluate.py
│
├── models/
│   └── trained_model
│
├── results/
│   ├── predictions.csv
│   ├── evaluation_metrics.csv
│   └── figures/
│
├── report/
│   └── final_report.docx
│
└── requirements.txt
```

*Note: The actual filenames and model file extension will depend on the selected project and implementation.*

## 8. Communication and Collaboration

- All members should agree on the project topic before starting individual tasks.
- Person 1 should share the problem definition and research findings with the group.
- Person 2 should prepare and document the dataset before model training begins.
- Person 3 should develop the model using the prepared dataset.
- Person 4 should coordinate evaluation and compile the final report.
- All members should review the results and contribute to the final presentation or demonstration if required.
- Members should share code, data documentation, and report sections through a common GitHub repository or shared folder.

## 9. Final Submission Checklist

- [ ] Project topic and business problem clearly explained.
- [ ] Project objectives defined.
- [ ] Literature review completed with proper citations.
- [ ] Dataset source and description included.
- [ ] Data preprocessing code completed.
- [ ] Sequential model implemented and trained.
- [ ] Predictions generated.
- [ ] Evaluation metrics reported.
- [ ] Tables and graphs included where appropriate.
- [ ] Business interpretation provided.
- [ ] Model limitations discussed.
- [ ] Recommendations and conclusion completed.
- [ ] Final report compiled and proofread.
- [ ] Code, dataset, and relevant results organised in the project repository.

## 10. Expected Outcome

At the end of this project, the group should have a working sequence-model-based solution to a real-world Business Intelligence problem. The project should demonstrate the complete process, from data collection and preparation to model development, evaluation, interpretation, and business recommendations.

The final solution should show not only how well the model performs but also how its findings could help a business make better decisions.
