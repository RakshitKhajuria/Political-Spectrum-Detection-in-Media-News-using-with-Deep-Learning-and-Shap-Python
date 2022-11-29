
# Political Spectrum Detection in Media News using with Deep-Learning and Shap Python.

The repository contains the data files and scripts corresponding to the paper "Neural Media Bias Detection Using Distant Supervision

## Data
 
- The data is from [Media Bias Group](https://media-bias-research.org/).
- "final_labels_MBIC.xlsx": MBIC's aggregated labels over all annotators based on majority vote (1700 sentences).
## Content

#### Columns:
- "text": sentences extracted from news articles and labeled in terms of bias and opinion.	
- "news_link": url to the news article from which the sentence is extracted.
- "outlet": news platform publishing the news article.
- "topic": news topic.
- "type": political orientation of news platform according to mediacloud.org.
- "label_bias": bias label for the sentence ("Biased" or "Non-biased").
- "label_opinion": opinion label for the sentence ("Expresses writer's opinion" or "Somewhat factual but also opinionated" or "Entirely factual".
- "biased_words": words marked as biased by the annotators.
## Requirements

        numpy>=1.9.2

        scipy>=0.15.1

        scikit-learn>=0.18

        matplotlib>=1.4.3

        pandas

        tensorflow

        nfx

        keras
        
        shap


## Installation


```bash
Clone this repository and unzip it.
- After downloading, cd into the notebook directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute it in Jupyter Notebook
```
    
