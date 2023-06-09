# Thesis DS&S 
This repository is a way to share my code for my thesis regarding the lexical diversity of human-written and ChatGPT-generated answers. Additionally, Machine Learning (ML) algorithms (Logistic Regression (LR), Support Vector Machine (SVM), Decision Tree (DT) and Naive Bayes (NB)) and a Deep Learning (DL) model (DistilBERT) were used for AI-generated text detection.

## Information
| Variables | Information                |
|:----------------:|----------------------------|
| *Name student*   | Ayça Kurt                  |
| *Student number* | u546753                    |
| *Committee*      | dr. Eva Vanmassenhove <br /> dr. Mirella De Sisto      |
| *Location*       | Tilburg University <br />  School of Humanities and Digital Sciences <br /> Department of Cognitive Science & <br /> Artificial Intelligence <br /> Tilburg, The Netherlands|

## Structure
- lexical_diversity.ipynb contains the code for the analysis regarding the lexical diversity.
- statistical_analysis.ipynb contains the code for the statistical analysis.
- ml_algorithms.ipynb contains the code for the detection of AI-generated text, specifically for the ML algorithms (LR, SVM, DT, NB).
- distilbert.ipynb contains the code for the detection of AI-generated text using DistilBERT.

## Abstract
Distinguishing between human-written and AI-generated text has become more challenging due to the advancements of Large Language Models. However, certain online tools claim to accurately differentiate between them. Building on findings from Machine Translation and Image Captioning, which found reduced lexical diversity in AI-generated text, this study investigates if text generated by ChatGPT shows similar patterns. Firstly, we measure the lexical diversity of human-written and ChatGPT-generated text using Type-token ratio, Yule's K, and Measure of Textual Lexical Diversity. The results show that ChatGPT-generated text has lower lexical diversity compared to human-written text, which is in line with previous research within the field of Natural Language Generation. Additionally, Machine Learning algorithms (Logistic Regression, Support Vector Machine, Decision Tree and Naive Bayes) and a Deep Learning model (DistilBERT) are used for AI-generated text detection. Successful detection is accomplished, with DistilBERT achieving the highest F1 score. These findings help us understand the lexical differences between humans and AI, and how to detect AI-generated text.

## Data
The _Human ChatGPT Comparison Corpus (HC3)_ can be found [here](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection).
