
# Dataset
The dataset contained by this site is the initial results of the mining process related to building a semantic network upon the Stack Overflow corpus. 

# The initial dataset:

* The file **is_relationship_cleaned_V0** contains is_a relationships extracted from Stack Overflow. The first column is the hypo, and    the second is the hypernym part of a relationship. The dataset is post-processed, which means that heuristics were applied to mitigate the linguistic and spelling mistakes contained in the original text.
* The file **checkAgainstWordnetHyper_V0** contains the relationships from the previous file completed the hypernym relationships provided by WordNet. The first column is the hyponym part of the relationship from Stack Overflow, the second column is the related word from the WordNet, the third column is the hypernym part from the Stack Overflow followed by the list of the common words and the hypernyms from the WordNet.
* The file **isGraph_withWn_V0.pdf** is the depiction of the very first graph.


The given files contain only a small part of the possible hypernym relationships, as the results grow, we'll post updates.
