# Screening of Neutrophil Activation Blockers Post Exercise

# Goal
Learn how to apply machine learning to analyze large RNA sequencing datasets and train a Random Forest model to identify potential drug hits based on gene expression variables.

# Summary
This project was my first dive into computational biology and AI-driven drug discovery. Using transcriptome data (GSE43856) from an exercise trial, looking at inflammation pre exercise and up to 48hrs post exercise, I analyzed gene expression changes pre and  post-exercise to spot inflammation markers such as TNF. I zeroed in on TNFSF14, which showed a 1.17-fold increase at 3 hours—hinting at neutrophil activation. I processed RNA-seq data in Python to ensure the correct mapping of probes using the GPL6947 platform which allowed for precise gene expression analysis. Next, I screened four ChEMBL compounds, that I found while doing research on potential TNFSF14 inhibitors. Then I used RDKit to define more chemical features on those ChEMBL compounds, such as molecular weight. I then built a Random Forest model, which I chose because it is beginner friendly, accurate, and able to handle large data sets effectively. This model ranked Thalidomide as a top comopund with a score of 0.45, indicating its likelihood to inhibit TNFSF14. This result is not novel as thalidomide is a well known and well described TNF blocker, however I learned a lot about the process of data analysis and using Random Forest to identify potential drugs for inhibition of TNF.
