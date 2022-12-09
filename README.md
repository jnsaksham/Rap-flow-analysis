# Rap-flow-analysis
Analysis of changes in flow in rap music between 1980-2015 and how has it evolved in terms of 2 parameters: Speed and Repetition

A system that investigates the degree of repetition of "stress patterns" during the utterance of a rap. Stress patterns are encodings of 0 and 1, depicting at which rhythmic position does the rapper stress or simply utter the lyrics

Dataset used: MCFlow

The system searches for similar patterns, tags them as same or different from the given pattern and computes relevant dependant variables for analysis over the years.

Steps to reproduce:
1. Download and save the MCFLow dataset from https://github.com/Computational-Cognitive-Musicology-Lab/MCFlow
2. Run proj_bash.ipynb to extract features from the dataset form .rap files (similar to .krn, specifically designed to be used with HumdrumR) - This step uses bash and humdrum
3. Run analysis.ipynb
