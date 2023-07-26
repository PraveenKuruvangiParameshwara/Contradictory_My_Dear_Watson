# Contradictory_My_Dear_Watson

# Detecting Contradiction and Entailment in Multilingual Text

# Introduction

Natural Language Inference : determine if the given hypothesis can be inferred from premise. 
Recognizing Textual Entailment : recognizing the relation
 between text fragments, relation holds when truth of 
one text fragment follows from another.
3-Way RTE : entailment, contradiction, neutral.
Easy for humans to understand context and perform 
inference but not for machines.
Aim: use language models on pairs of sentences in 15 different languages 
to find if they are entailing, contradictory, or neutral.

# Data Source

Data sourced from the Kaggle competition, “Contradictory, My Dear Watson.”
Format: Text-based CSVs
Training Set: 12120 instances
Test Set:  5195 instances.
Attributes: Premise, Hypothesis, Language and Label
Label: 0 - Entailment, 1 - Neutral, 2 - Contradiction
Languages: 15 (English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, etc)
