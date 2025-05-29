# GeneticPieces2Vec
Deep learning method for extracting vector representations of genes.

The genetic improvement of the African oil palm (*Elaeis Guineensis Jacq.*) is essential to increase the productivity and sustainability of the crop, especially in Colombia, where it represents a key economic activity. This is usually carried out using different statistical methods that represent genetic information and use it to streamline breeding cycles. However, these methods have limitations in biological interpretation, as they analyze genetic variants in isolation and without considering their functional context.

To overcome these limitations, this thesis proposes a deep learning model based on the *Skip-gram* architecture of *Word2Vec* called **GeneticPieces2Vec**. This was trained from a set of 3,236,681 genes corresponding to a population of 1003 plant materials of *Elaeis Guineensis Jacq.*, to generate biologically enriched vector representations of DNA sequences.

The developed workflow included the acquisition and annotation of genomic data, tokenization using *Byte Pair Encoding*, and model training with hyperparameter optimization. The evaluation of the model showed outstanding performance, with an intrinsic AUC of 0.96, and extrinsic evidence of biological relevance: positive correlation with physicochemical properties of amino acids and negative correlation with population genetic distances.

These results indicate that the model is capable of extracting functionally significant information from genetic sequences, which makes it a promising tool to accelerate the genetic improvement of *Elaeis Guineensis Jacq.*


Auth:

Sebastian Ariza Parra

Msc. Juan Sebastian Malagón Torres - https://co.linkedin.com/in/juan-sebastian-malagón-torres-86039a164

Phd. Ivan Mauricio Ayala Diaz  - https://co.linkedin.com/in/ivan-m-ayala-diaz-78a25246
