# Clinical Trial Analysis Project
This Jupyter notebook contains Python code that analyzes data from a Phase I clinical trial. The notebook addresses the following key questions.

1. **Frequency and Severity of Adverse Events:** Summarizes the frequency and severity of adverse events observed during Phase I of a clinical trial.
2. **Dose-Related Trends in Adverse Events:** Investigates whether there are any dose-related trends in the occurrence or severity of adverse events among participants in the trial.
3. **Recommendations for proceeding to Phase II Clinical Trials:** Provides recommendations for proceeding to Phase II of the clinical trial based on the analysis of Phase I data. (Example external research and insights are incorporated to support these recommendations for our sample case).


## Table of Contents
1. [Quick Overview](#QuickOverview)
2. [Requirements](#Requirements)
3. [Data](#Data)
4. [Contact](#Contact)
5. [Tutorial](#Tutorial)
6. [Usage Agreement](#UsageAgreement)

## Quick Overview <a name="QuickOverview"></a>
The notebook is organized into the following sections:
1. **Data loading and processing:** Loads the clinical trial data and prepares it for analysis. This includes handling missing values, data cleaning, and organizing the data for subsequent analysis.
2. **Frequency and Severity fo Adverse Events:** Various methods employed to understand the frequency and severity of adverse events reported during Phase I clinical trials. Visualizations and summary statistics are provided to illustrate these findings.
3. **Dose-Related Trends:** Explores potential dose-related trends in adverse events among participants. Data visualization techniques are used to identify any patterns or correlations between dose levels and adverse event occurrences.
4. **Recommendations for Phase II:** Provides recommendations for advancing to Phase II of the clinical trial based on the analysis conducted in the previous sections and supported by outside research and best practices in clinical trial design and management.

## Requirements <a name="Requirements"></a>
To run the code in this notebook, please have the following dependencies installed:
- Python 3.11.7
- Jupyter Notebook
- Pandas
- Matplotlib

Clone this repository to your local machine and open the notebook using Jupyter Notebook. Follow the instructions within the notebook to execute the code cells and view results.

## Data <a name="Data"></a>
Here, we have an example of what our data looks like. Your data may look different. Please take note of the columns being used for each analysis and adjust accordingly.

*Sheet 1 (Participants)*
- ParticipantID
- Age
- Gender
- Ethnicity
- Weight
- Height
- MedicalHistory
- BaselineVitals
- InclusionCriteriaMet
- ExclusionCriteriaMet
- Accepted
- Started
- Finished

*Sheet 2 (Doses)*
- DoseID
- ParticipantID
- DoseNumber
- AdministrationDate
- AdverseEvents
- SeverityofAdverseEvents
- DurationofAdverseEvents
- VitalsPostDose
- LabResultsPostDose

## Contact <a name="Contact"></a>
*Got any questions? Feel free to contact us at:*

**Twitter:** [@jaelkhader](https://twitter.com/jaelkhader)

**Email:** [jaelkhader@gmail.com](jaelkhader@gmail.com)

## Tutorial <a name="Tutorial"></a>
- In progress

## Usage Agreement <a name="UsageAgreement"></a>
- In progress