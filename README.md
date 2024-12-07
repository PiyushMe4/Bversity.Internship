# Bversity.Internship

# Drug Similarity Analysis for Methicillin-resistant Staphylococcus aureus Bacteria




## Project Overview
This repository contains the workflow and results of a study to identify drugs structurally similar to Linezolid for the treatment of Methicillin-resistant Staphylococcus aureus Bacteria (MRSA). MRSA is a type of bacteria resistant to many antibiotics, making infections difficult to treat. It cancause various infections, but also severe conditions like pneumonia and bloodstream infections.
Linezolid is an oxazolidnone antibiotic that inhibits bacterial protein synthesis by binding to the 50S ribosomal subunit, preventing the formation of functional ribosomes.
## Problem Statement
Linezolid, a protein synthesis inhibitor, is used for effective treatment for MRSA. Identifying structurally similar drugs can offer alternarive therapeutic options and contribute to drug discovery effforts. This study employs 2D and 3D confromer analyses for this purpose. 
## Workflow and Tools
- **Data Source** : PubChem Database
- **Tools Used** : KNIME for computational analysis, leveraging nodes for feature extraction, similarity scoring, and visuzalization.
- **Analysis Methods** :
   - **2D similarity** : Tanimoto Coefficients
   - **3D Similarity** : Root mean square deviation (RMSD)
## Key Steps
1. **Data pre-processing** :
- Molecule retrieval from PubChem.
- Conversion to standard format (e.g: SMILES, SDF).
- Structural normalization.
    
2. **Feature extraction** : Calculation of 2D and 3D molecular descriptors
3. **Similarity analysis** : Scoring based on Tanimoto (2D) and RMSD (3D).
4. **Visualization** : Scatter plots and heatmaps for interpretability.
5. **Filtering** : Shortlisting compounds with high similarity scores (__Blue__) (e.g: Tanimoto score - 0.92)
## Results
- **Yellow** : Indicates low similarity in heatmap
- **Blue** : Indicates high similarity in heatmap
## Conclusion
This project simply demonstrated the power of computational tools in identifying structurally similar drugs. By combining 2D fingerprint analysis with 3D spatial alignment, a well-rounded approach to molecular similarity evaluation was acheived. The findings provide insights into potential linezolid alternatives for MRSA and pave the way for further research in drug discovery.
