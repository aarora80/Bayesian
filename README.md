# Bayesian
Disease Diagnosis Using Bayesian Networks

Disease Diagnosis Using Bayesian Networks
In this project, I developed a Bayesian Network model to predict the likelihood of a disease based on various symptoms and demographic factors. The goal was to create a probabilistic model that could assist in medical diagnosis by considering multiple factors and their interdependencies.

Key Components:
Model Structure:

The Bayesian Network includes nodes for various symptoms (Fever, Cough, Fatigue, Difficulty Breathing), demographic factors (Age, Gender), and health indicators (Blood Pressure, Cholesterol Level).
The central node, Disease, is influenced by these factors, which collectively determine the probability of a particular outcome.
Conditional Probability Distributions (CPDs):

Each node is parameterized with CPDs, which define the probability of each state given its parents. For simplicity, the initial CPDs were set to equal probabilities, but these can be refined with real data.
For instance, the CPD for the Disease node considers the combined influence of symptoms and demographic factors.
Inference:

Using the Variable Elimination algorithm, the model performs exact inference to compute the posterior probabilities. This allows us to predict the likelihood of an outcome (e.g., presence or absence of a disease) given observed evidence.
In the example, the posterior probability of the outcome is computed given the presence of fever and cough.
