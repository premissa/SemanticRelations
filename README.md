# Abstract
Communication between a software development team and business partners is often a challenging task due to the different context of terms used in the information exchange. The various contexts in which the concepts are defined or used create slightly different semantic fields that can evolve into information and communication silos. Due to the silo effect, the necessary information is often inadequately forwarded to developers resulting in poorly specified software requirements or misinterpreted user feedback. Communication difficulties can be reduced by introducing a mapping between the semantic fields of the parties involved in the communication based on the commonly used terminologies. Our research aims to obtain a suitable semantic database in the form of a semantic network built from the Stack Overflow corpus, which can be considered to encompass the common tacit knowledge of the software development community. Terminologies used in the business world can be assigned to our semantic network, so software developers do not miss features that are not specific to their world but relevant to their clients. We present an initial experiment of mining semantic network from Stack Overflow and provide insights of the newly captured relations compared to WordNet.

# Dataset
The dataset contained by this site is the initial results of the mining process related to building a semantic network upon the Stack Overflow corpus. 

# The initial dataset:

* The file **is_relationship_cleaned_V0** contains is_a relationships extracted from Stack Overflow. The first column is the hypo, and    the second is the hypernym part of a relationship. The dataset is post-processed, which means that heuristics were applied to mitigate the linguistic and spelling mistakes contained in the original text.
* The file **checkAgainstWordnetHyper_V0** contains the relationships from the previous file completed the hypernym relationships provided by WordNet. The first column is the hyponym part of the relationship from Stack Overflow, the second column is the related word from the WordNet, the third column is the hypernym part from the Stack Overflow followed by the list of the common words and the hypernyms from the WordNet.
* The file **isGraph_withWn_V0.pdf** is the depiction of the very first graph.


The given files contain only a small part of the possible hypernym relationships, as the results grow, we'll post updates.

# Papers

[1] László Tóth, Balázs Nagy, Tibor Gyimóthy and László Vidács 2020. Mining Hypernyms Semantic Relations from Stack Overflow in IEEE/ACM 42nd International Conference on Software Engineering Workshops (ICSEW'20), May 23-29, 2020, Seoul, Republic of Korea. ACM, New York, NY, USA. 7 pages. https://doi.org/10.1145/3387940.3392160
