# Single Document Extractive Summarization using Domination in Hypergraphs.

Extractive summaries are formed by picking up the most important sentences and phrases from a document. This research project aims to generate an extractive summary by creating a sentence hypergraph where each sentence represents a node and the edge is a keyword or a named entity that contains the sentences in which it occurs. Once the hypergraph is created, sentence extraction is formulated as a dominating set problem.

|![hypergraph image](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/hypergraph.jpeg)|
|:--:|
|*Keyword Sentence Hypergraph*|

1. The entire NLP pipiline for this project along with the calculated results can be found [here](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/all_rouge_final.ipynb). (This is the only file whose results have been published.) The method employed is depicted in the diagram below.

|![architecture diagram](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/architecture_diag.jpeg)|
|:--:|
|*Architecture diagram*|

2. Another approach was explored for the creation of hypergraphs. TF-IDF has been used [here](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/tf_idf_%2B_domination.ipynb) to find the keywords and then domination has been applied to the constructed hypergraph.
3. Hill climbing algorithm has been used [here](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/hill_climbing_%2B_hypergraph_creation.ipynb) to perform sentence clustering and then create a hypergraph using these clusters as edges.
4. [This](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/file_1.ipynb) code file is an attempt to explore various properties of hypergraph and simulate textrank algorithm.    
5. This [file](https://github.com/aabhapingle/summarization-using-domination-in-hypergraphs-/blob/main/Dataset_creation.ipynb) contains code to convert the original text data (like .txt files) into a dataframe. 


A reseach paper related to the same is currently under review.


