# Sentence Similarity

Topics:

1. Training models for Sentence Similarity task using sentence-transformer library. 

2. Using pretrained paraphrasing model.

2. Through this notebook, we learned to train **bert-base**, **distilroberta-base**, **microsoft/MPNET** for downstream task like sentence similarity.

3.  **What makes our project special?** We are using a pretrained paraphrasing models to paraphrase a dataset. Then we use our fine-tuned sentence similarity models to evaluate how close the meaning of paraphrased query is to original sentence. Through this process, we determine accuracy of paraphrasing model. In a way, we are using similarity models as a metrics to test paraphrase model.
