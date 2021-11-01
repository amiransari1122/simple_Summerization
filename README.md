# Simple Summerization
Two basic algorithms for Text Summarization can be Frequency based method and Cosine Similarity based summarization method. They are not Learning base just via sentences and tokens analysis.
1)Frequency base method seperate main words in each senetences and compute weight of each words in sentence and sum them. Now we have sentence scores and can select some of them as summary.

2)Cosine Similairy create main words vectors of each sentece and calculate similary(dot product) between them. The senetence with larger similary with this vector has more importance and score.
