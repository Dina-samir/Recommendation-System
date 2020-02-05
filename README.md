# job-titles-recommendation-by-skills

 Recommend Job titles according to user skills 

 Here is two Notebooks for find more similar jobs to user skills, and find skill set gab between your skills and job  skills.
 
1)I used word2vec for feature engineering.Then use n_similarity between inserted skills with each Dataset row skills after remove all nan and deplicated rows.

2)I used CountVectorizer for feature engineering. 
Then use cosine_similarity between inserted skills(after tranform it by Vectorizer) 
with each Dataset skill row after remove all nan and deplicated rows.
