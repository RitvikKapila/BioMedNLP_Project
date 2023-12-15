# BioMedNLP_Project

Repo to house all code for MED 277 BioMed NLP course at UCSD, Fall 2023. 

## Project Description
Employing LLMs to help assist medical diagnosis, and prevent missed, incorrect, or delayed diagnoses through this.
* Take cases where final diagnosis contains pulmonary embolism.
* Look at time-series data of daily summaries/notes for a patient, and give model the cumulative data till that date about that patient. 
* If the model correctly predicts pulmonary embolism before (or at the same time/with the same data as) when the physicians mention it in their daily summary, we treat this as a positive result.

## Data
MIMIC-III dataset used. Cases where Pulmonary Embolism is mentioned in the final diagnosis are extracted.

## Model
OpenAI GPT-3.5 turbo used, with API.