# Prediction of Cognitive disease progression in Parkinson's patients
Parkinson’s disease is classically defined as a movement disorder, patients may often experience some cognitive decline ranging from mild impairment to dementia. The severity of one’s cognitive impairment has a major impact on quality of life, cost of care, and survival. This project  uses sequential machine learning, explainable AI to shed light on how cognitive impairment in Parkinson’s disease progresses and to identify biomarkers that may indicate early on which patients will develop the most severe cognitive dysfunction and disabilities.

# Project Contributors
Soumya Goswami and Edgar Bernal

# Code description
ppmi_CognitionFactors.ipynb- Identifies the cognition features or biomarkers that affects the state (Normal, MCI, Dementia)
<br>
ppmi_steady.ipynb          - Uses PPMI and steady dataset to understand the equivalence between UPDRS and MDS-UPDRS factors affecting cognition state
PPMI_Sequential_modelling.ipynb -Uses sequential LSTM to predict on future cognition states from present cognition factors and present cognition states.
