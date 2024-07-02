# Learnosity Automated Student Assessment Assement

The main goal of the automated essay grading system is to reduce human effort and improve consistency.

### Assumptions 

- The human given grades are perfect, non biased and follow the rubic. 

### Summary of Book

#### How Does the Auto Score Compare to Human Scoring?

- Quadratic Weighted Kappa (QWK) was the primary metric used to evaluate the model scores against the human scores.
- It was found that neither model performed particularly well compared to state-of-the-art approaches.
- Model 1 was slightly better across the rubric criteria.

#### How to Improve Automated Assessment Scoring

There were several considerations on how to improve Automated Essay Scoring (AES). Research indicated that utilizing a pre-trained BERT model would yield the best results.

Other methods considered included using pre-trained word embeddings, such as GLOVE, to extract features from the essay text and then train a multi-classification model, or utilizing large language models (LLMs) like ChatGPT or Llama to automate essay scoring. However, research suggested that fine-tuning a BERT model with the given data would achieve better performance.

#### Does AES Work?

Yes, the main goal of Automated Essay Scoring (AES) is to reduce human effort and improve consistency. While AES does reduce human effort, 
research and the model created for this task found that AES is more consistent than human raters. The two human graders had a QWK score of 0.724 
when compared with each other, while the model created for this task had a QWK score of 0.79. Additionally, research has shown that state-of-the-art models (SOTA) 
have achieved QWK scores of 0.84.

:::
```{tableofcontents}
```
