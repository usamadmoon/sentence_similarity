# sentence_similarity
Comparison of Manual Sentence similarity VS Bert Sentence Transformer Similarity

# BERT Sentence Transformers similarity

Transformers transforms the sentences to probablistic vector of each word against a pre-trained model by Google against a huge dataset.
This implies that the probabilities of each word is calculated against various variations of a same word.
In the example, we had two sentences with only one same word i.e. Python, but multiple similar words like creating/build, application/program, AI/Artificial Intelligence etc. 
This assigns relative weights against each word in the sentence.
When the cosine similarity is calculated we get 91% similarity which is the value we were expecting.

# Legacy Rule Based Cosine Similarity

We converted the sentences to a normal count vector that will store the count of each word, then we searched for the common word in both sentences and calculated the cosine similarity.
The result we got were 8% only which is the right similarity of the given sentences but it is not sementically correct.

# Comparison Results

The comparison shows the ability and potential of the transformers dataset to get sementical results.
