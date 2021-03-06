# ProteinFunctionPrediction
[Protein function prediction with the Gene Ontology](https://github.com/SchaefJo/ProteinFunctionPrediction/blob/master/ProteinFunctionGO_ProjectReport.pdf)

Proteins have an important role in living organisms. They catalyze reactions, transport molecules and act as messengers for information. In drug development and drug repurposing, knowing the multiplicity of functions of a protein can prevent side effects.

We predicted protein functions according to the Gene Ontology (GO), a standardized vocabulary to describe the function of genes and gene products as a hierarchical acyclic graph. As features, we used Sequence-to-Vector embeddings(SeqVec), a 1024 long vector that uses Language Processing on the sequence. In this paper, we compare a flat approach that predicts all classes independently, a hierarchical approach that starts at the top of GO and a Path Propagation Algorithm, which is a flat approach but propagates all probabilities until the top of the graph. The algorithms are compared on a data set consisting of 1300 proteins.

The balanced accuracy from the Path Propagation, which is the best of the three algorithms is 0.71 ± 0.14. The F1-score of Path Propagation is 0.4 ± 0.23.


This was an university project of mine done in my 2nd and 3rd semester in undergrad.
