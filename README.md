# Screening-of-Neutrophil-Activation-Blockers-Post-Exercise

# Goal
Use AI to screen compounds that could dampen neutrophil activation in response to exercise-induced inflammation, targeting drug discovery for conditions like muscle damage or overtraining syndromes.

# Summary
This project was my first dive into computational biology and AI-driven drug discovery, guided heavily by Grok 3 from xAI. Using neutrophil transcriptome data (GSE43856) from an exercise trial, I analyzed gene expression changes post-exercise to spot inflammation markers. I zeroed in on TNFSF14 (LIGHT), which showed a 1.17-fold increase at 3 hours—hinting at neutrophil activation. With Grok 3’s help, I wrangled RNA-seq data in Python (Pandas), mapped probes with GPL6947, and screened four ChEMBL compounds (e.g., Thalidomide) using RDKit for chemical features (MolWeight, LogP). I then built a Random Forest model to rank blockers, with Thalidomide topping the list (score: 0.45). Plotting the results with Matplotlib sealed the deal. As a newbie, Grok 3 was my co-pilot—debugging code, picking tools, and shaping the workflow. Check out the notebook, plot, and ranked hits below!
