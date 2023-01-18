# NLP-powered-Recommender-System-using-Knowledge-Graph-for-Tourism

Dissertation Project for the Master Degree in Data Science.

> Raw Data & trained Transformer models can be found in the uploaded text file to be downloaded form Google Drive.

## Description of Project

In this project, we built a recommender system using the state-of-the-art RoBERTa model and knowledge graphs. The dataset for this study is open-source and can be downloaded from Google Drive. The constructed knowledge graph provided the flexibility to recommend packages by easily traversing the graph network. 


## Evaluation

Experimentation with the RoBERTa model were done and evaluated. It’s found that the RoBERTa model can achieve high performance with small amount of training data and short training time. The fine-tuned model scored 76.61%, 70.37% and 73.35% for precision, recall and F1 score, respectively.


## Future Work

We propose to annotate a bigger dataset with more entities included within the text. This will help the model to create more accurate contextual embeddings, hence improved entity recognition.

Including POS tagging with the entities labels is desirable, as this will help the model to understand the lexical attributes of the words in the sentence. For RoBERTa training, we suggest exploring other hyperparameter tuning to check if this produces better results.

Incorporating a rating-based attribute to the entities will allow to better filter the entities and give the user more flexibility in determining their constraints.
