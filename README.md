# Master Thesis R Script and data files

This repository contains the R scripts used in my master thesis titled "Exploring The Dark Proteome: Microproteins."

Description

The field of protein science historically disregarded short proteins, termed microproteins, due to an arbitrary size cutoff of 100 amino acids. However, recent advances in ribosomal profiling, proteomics, and bioinformatics have revealed thousands of unannotated proteins, likely translated from short open reading frames (sORFs) under 300 base pairs. Microproteins, possessing diverse cellular functions from mRNA decay to muscle contraction, have emerged as potentially significant players in human health and disease, analogous to the discovery of small non-coding RNAs. Many microproteins originate from noncanonical ORFs, challenging the traditional understanding of eukaryotic mRNA being monocistronic. Given that many microproteins fall below the size threshold (< 50 aa) required for globular protein structure, their place within the protein spectrum remains unclear. The current project aims to map the physico-chemical properties of microproteins from humans by constructing a reference data set of different protein classes, including globular proteins, membrane proteins, intrinsically disordered proteins (IDPs), peptides and microproteins. Physico-chemical properties like net charge, hydrophobicity, etc. are utilized to cluster these proteins, utilizing dimensionality reduction techniques such as tSNE to visualize their distribution in the proteome landscape. Similar approach is also applied on prediction scores obtained from tools like IUpred2A, DeepTMHMM and GRAVY. Additionally as control random snippets are generated from the canonical proteins and are visualized on dimensionality reduction plots to see if length has an effect on the clustering of microproteins with these random snippets. Finally, for structural analysis, AlphaFold was employed to predict the structures of 500 randomly selected microproteins. 


## Data Files

The data files for this project are available on OneDrive. You can access them using the following link:

[Access Data Files on OneDrive](https://kuleuven-my.sharepoint.com/:f:/r/personal/namrata_student_kuleuven_be/Documents/Master_Thesis_Data_Files?csf=1&web=1&e=OInI2s)
