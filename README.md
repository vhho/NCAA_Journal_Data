# NCAA Journal Data
## Reference data for the NCAA journal article, 
## "VIETNAMESE SENTENCE FACT CHECKING BASED ON THE KNOWLEDGE GRAPH, DEEP LEARNING AND INFERENCE RULES"

Figure 5 below shows the proposed model for verifying the accuracy of Vietnamese sentences by combining Knowledge Graph with Logic Programming Language, utilizing the Triple Classification task based on the KG-BERT model. 

![image](https://user-images.githubusercontent.com/30404000/233814923-2c4e42f4-d5c3-4bae-a6da-73750ce6568e.png)

The data used in this paper includes the following files:

**1) Original KG:** This is a repository of Vietnamese-based triples used as evidence to verify information.

**2) Logical Rules:** This contains the Logical Rules used by Algorithm 2 to infer new triples, Inferred Triples, in the Datalog language.

**3) Complete KG:** This contains the complete data set, Complete KG, which includes the original dataset, Original KG, plus the newly inferred and conflict-tested triples, Validated Triples.

**4) Claim Sentences:** This contains the sentences for fact-checking.
