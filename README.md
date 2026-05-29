# Measuring Spatial Injustices_BERTopic Analysis
Supports: “Measuring spatial injustices: a systematic review of topics, metrics, and normative foundations in applied geography and spatial research” (to be submitted for peer review).
 
## Overview
The goal of this research is to systematically review applied geographic and spatial science literature on topics of justice, specifically measuring injustices in spatial distributions of benefits and burdens. Using topic modelling with BERTopic, approximately 1,400 peer-reviewed journal articles were analysed as part of the screening process for this review. Additionally, medoid papers were extracted for each topic to be used for qualitative analysis (coding in MaxQDA). This supplement to the paper contains the code for the BERTopic model. 
 
## Citation
Please cite this repository as: DOI/Zenodo
 
## Usage
- The model can be run as is on Google Colab (using CPU).
- Load the input file into your Google Drive storage.
- The output file presents the assignment of papers to topics and medoid selection (papers_with_topics_and_medoids.csv)
- Given the non-deterministic components in the embedding model, UMAP, and clustering model, instantiations produce slight variations in the results with time. The Adjusted Rand Index (ARI) in the test section of the code can be used to compare different instantiations over time.
  
## Contributors
Helena Schuch, Department of Geography and Regional Research, University of Vienna, [ORCID](https://orcid.org/0009-0007-2378-7378).
 
## Contact
helena.schuch@univie.ac.at
 
## Acknowledgments and Sources
A detailed description of BERTopic is available at: maartengr.github.io/BERTopic/
