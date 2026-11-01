# MediLabelAI
NLP project for classifying medical specialties from clinical transcriptions using Python.
MediLabelAI: Medical Specialty Classification using NLP
MediLabelAI is a Natural Language Processing project focused on automating the categorization of unstructured medical transcriptions into their respective medical specialties.
🚀 Project Overview
The dataset used for this project is the MT Samples dataset, containing nearly 5,000 clinical transcriptions. Medical text is notoriously difficult to categorize due to complex terminology; MediLabelAI addresses this by building a focused classification pipeline.

Key Features:
Large-Scale Data: Processed 4,999 records of medical transcription data.

Targeted Focus: To improve accuracy, the project focuses on the top 6 high-volume specialties, filtering out low-frequency categories to reduce noise in the model.

Medical Context: Handles specialized fields ranging from Surgery and Radiology to Gastroenterology and Cardiovascular/Pulmonary medicine.

🛠️ Technical Stack
Language: Python

Data Handling: Pandas, NumPy

Text Processing: NLTK, Regex (re)

Data Visualization: Matplotlib, Seaborn

📊 Exploratory Data Analysis (EDA)
Initial analysis revealed 40 unique medical specialties. To build a more effective model, I focused on the most frequent categories:

Surgery: 1,103 samples

Consult - History and Physical: 516 samples

Cardiovascular / Pulmonary: 372 samples

Radiology: 273 samples

General Medicine: 259 samples

Gastroenterology: 230 samples

🧹 Preprocessing Pipeline
The project implements a cleaning routine to prepare raw medical text for analysis, including:

Removal of special characters and numbers using Regular Expressions.

Tokenization and stop-word removal using the NLTK library.

Focused analysis on the description and transcription columns to extract meaningful features.
