<h1 align="center">Assignment - Sentiment Analysis</h1>

## Task Overview

**Given a sample review, the task is to extract insights called "subtheme sentiments," which reflect sentiments towards specific aspects of a service or problem described in the review.**

## Approach

### Data Compilation
- **Dataset Construction**: Compiled all subthemes and their sentiments from each review into a dataset, where the first column contains the review text and the second categorizes the sentiments as positive or negative.

### Algorithm Implementation
- **Techniques Used**: Utilized traditional machine learning algorithms and fine-tuning of Large Language Models (LLMs).

### Classifier Development
- **Specific Classifiers**: Constructed individual classifiers for subthemes such as 'value for money', 'garage service', and 'ease of booking', which output the sentiment associated with these subthemes.

### Model Fine-Tuning
- **GPT-Neo-125M**: Fine-tuned on the entire dataset for sentiment analysis.
- **Llama-2**: Adapted and fine-tuned for the task on a subset of 100 reviews formatted as questions and answers.

## Results

- **GPT-Neo Model**: Fine-tuned for three epochs and tested locally. Due to limited training, accuracy may vary.
- **Llama-2 Model**: Demonstrated potential in handling subtheme sentiment tasks effectively.

## Improvements Suggested

- **Introduction of Neutral Category**: To better classify reviews not directly related to the subthemes, introducing a 'neutral' sentiment category could be beneficial.
- **Extended Training**: Increase the number of training epochs and use a GPT-Neo model with more parameters to enhance performance.

## Links to Deployed Models

- [GPT-Neo Fine-Tuned Model](https://huggingface.co/yashmathur0310/GPT-Neo-FineTuned)
- [Llama-2 Fine-Tuned Model](https://huggingface.co/yashmathur0310/Llama-2-100)

---

Made by - Yash Mathur
