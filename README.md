It was a task (assignment) for Natural Language Processing Course (Spring 2020). 
The task was to implement a Named Entity Recognizer (NER) using Conditional Random Fields (CRFs) in Python.

The main steps followed to achieve the goal of this assignment were: 

1) Data preprocessing to transform raw data into a format suitable for input to the CRF model,
2) Feature extraction to discover what latent signals might be helpful to identify entities,
3) Training of the CRF model with selected features, and
4) Classification using CRF

For the assignment, training and development sets came from WNUT corpus, and test data was from an anonymous social media platform. The format of the data was the same across all three different sets. Each row includes one word and the entity tag which was assigned to that word, and posts were separated with blank lines. The data used IOB encoding, where each named entity tag was prefixed with a B-, which means beginning, or an I-, which means inside. The O tag is for non-entities. 


