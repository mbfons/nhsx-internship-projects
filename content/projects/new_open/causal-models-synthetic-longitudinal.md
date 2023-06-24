---
remote_theme: nhsx/nhs-io-theme
title: Causal Models to Generate Longitudinal Data
description: NHS England PhD Internship - Causal Models to Generate Longitudinal Data
permalink: /causal-models-synthetic-longitudinal/
---

# Causal Models to Generate Longitudinal Data

**Keywords:**  Synthetic, DAGs, TabularData

**Need:**  The ability to analyse and build tools to support patient pathways is low, often due to data access.  Creating synthetic patient pathways would be one way to resolve the access issue, at least for use where the fidelity of the data can be low.  The field of synthetic longitudinal data is complicated due to the temporal information making identifiability much higher than simple transactional data, as well as requiring the models to deal with a higher order of freedom.  This project would seek to investigate the generation of synthetic longitudinal data using causal models or probabilistic graph models such as Bayesian Networks. 

**Current Knowledge/Examples & Possible Techniques/Approaches:**  [Generating high-fidelity synthetic patient data for assessing machine learning healthcare software](https://www.nature.com/articles/s41746-020-00353-9) is a paper of particular interest relating to the CRPD work on generating synthetic data.    The work is further evaluated in evaluating a [“Longitudinal Synthetic Data Generator using Real World Data”](https://cprd.com/sites/default/files/2022-04/Wang%20et%20al%20preprint.pdf)

Directed Acyclic Graphs (DAGs) are commonly used to capture the causal effects of a network.  In most real world contexts DAGs are often created from or expanded by subject matter knowledge.  Chapter 6 of the 2020 thesis by Arnold, K.F titled [Statistical and simulation-based modelling approaches for causal inference in longitudinal data](https://etheses.whiterose.ac.uk/27245/1/Arnold_KF_Medicine_PhD_2020.pdf) discussed DAGs in microsimulation models 

An additional advantage of the DAG representation is the ability to adjust the DAG to address bias in a dataset with the potential to produce a fair dataset even when real world data collection has known issues.


**Related Previous Internship Projects:** [SynthVAE](https://github.com/nhsx/SynthVAE)

**Enables Future Work:**  Simulation of Patient Pathways or multi-year EHR tables

**Outcome/Learning Objectives:**   Open code and report demonstrating potential and evaluation of these techniques to generate longitudinal data.  

**Datasets:** Open datasets such as those on Opendata.nhsbsa.net 

**Desired skill set:**  When applying please highlight any experience around work with synthetic generation, probability & graph models, coding experience (including any coding in the open), any other data science experience you feel relevant.


---
Return to list of [all available projects](https://nhsx.github.io/nhsx-internship-projects/).