
# Quantitative Structure-Activity Relationship(QSAR) of anticancer peptides using Random Forest

*In this project, a random forest-based model was built to help classify peptides as either anticancer peptide or non-anticancer peptide.
Peptides are short chains of amino acids linked by peptide bonds, typically consisting of 2 to 50 amino acids. They are smaller than proteins and play a variety of roles in biological processes. In cancer treatment, peptides have emerged as promising therapeutic agents due to their high specificity, low toxicity, and the ability to be engineered for targeted therapy.* 


## Dataset
The data consists of information on 4,157 peptide sequences obtained from 'Alternate Training Dataset.txt' file of [this research paper](https://www.sciencedirect.com/science/article/pii/S0933365722001142?casa_token=p14t_jmNhagAAAAA:2lN86aLI--EBzDuRDs9mwdqnkou0sNYIvMy_AC2WvesZZkc5_KsbmD3qpB1cGnYt4p3LJyY-)  

The predictive model was built based on the Amino Acid Composition of the various peptides
## Tools/Skills Used
-Jupyter Notebook

-Pfeature

-Pandas

-CD-HIT

-Numpy

-Scikit-learn

-Data wrangling

-Linux

-Matplotlib

-Seaborn
## Key Insights
Based on the feature importance on Amino Acid Composition(AAC), the presence of Glutamic acid(AAC_E),Cysteine(AAC_C), Aspartic acid(AAC_D) or Lysine(AAC_K) in a peptide sequence contributed the most to the classification of a peptide as either anticancer or non-anticancer based on the model.
