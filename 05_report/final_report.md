# From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes
Student: Bahian, Celine R.
Disease: HIV-susceptibility
Gene: CC5
Documented Variant: NM_001394783.1:c.554_585del
# Disease background
Human Immunodeficiency Virus (HIV) is a disease that weakens the immune system by attacking CD4⁺ T cells, which help the body fight infections. To infect these cells, HIV first attaches to the CD4 receptor and then uses the CCR5 receptor as a co-receptor to enter the cell. As the virus continues to multiply, the number of CD4⁺ T cells decreases, making the body more vulnerable to infections and other diseases. 
A well-known genetic variant of the CCR5 gene is the CCR5 Δ32 mutation, which is caused by the deletion of 32 nucleotides in the coding sequence. This mutation produces a shortened and nonfunctional CCR5 protein that cannot be properly expressed on the cell surface. Without a functional CCR5 receptor, most CCR5-tropic HIV-1 strains have difficulty entering CD4⁺ T cells. Because of this, people who inherit two copies of the Δ32 mutation have a high level of natural resistance to many HIV infections.

# Gene and Normal Protein Function
The CCR5 gene is located on chromosome 3 (3p21.31) and encodes the C-C chemokine receptor type 5 (CCR5), which is a receptor found on the surface of immune cells such as CD4⁺ T lymphocytes, macrophages, and dendritic cells. Its main function is to bind chemokines and regulate the movement of immune cells during inflammation and immune responses. The CCR5 receptor also acts as a co-receptor for HIV-1, allowing the virus to enter CD4⁺ T cells. Because of this important role, changes in the CCR5 gene can affect both immune function and susceptibility to HIV infection.

# Documented Mutation
The documented mutation analyzed in this study is the CCR5 Δ32 variant, a 32-base pair deletion in the CCR5 coding sequence. It is recorded as NM_000579.3:c.554_585del32 and results in the protein change p.Ser185fs. This deletion causes a frameshift mutation, which changes the reading frame, alters the downstream amino acid sequence, and produces a premature stop codon. As a result, the mutant CCR5 protein becomes truncated and is predicted to lose its normal receptor function.

# Hypothesis
If the documented CCR5 Δ32 mutation is introduced into the wild-type CCR5 coding sequence, the deletion of 32 nucleotides is expected to cause a frameshift mutation. This will change the downstream codons, produce a premature stop codon, and result in a shorter, truncated CCR5 protein with reduced or lost normal receptor function.

# Methods
This study used Galaxy to analyze the CCR5 Δ32 mutation and compare it with the normal CCR5 gene. The wild-type (WT) CCR5 coding sequence (NM_000579.3) was imported into Galaxy and kept as the reference sequence throughout the analysis. A separate Galaxy history was created to organize the WT, documented mutant, and artificial mutant datasets. 
The documented CCR5 Δ32 mutation was created by manually deleting 32 nucleotides (c.554–585) from a copy of the WT sequence. The WT and mutant CDS were then translated into protein sequences using the Transeq tool in Galaxy. The resulting proteins were compared based on protein length, reading frame, amino acid changes, and the presence of a premature stop codon. 
A second experiment was also performed by creating an artificial one-nucleotide deletion (c.4delG). The artificial mutant was translated and compared with both the WT and documented mutant proteins to observe how different frameshift mutations affect the amino acid sequence and the predicted function of the CCR5 protein. 

# Results
The Galaxy analysis showed clear differences between the wild-type (WT) and the two mutant CCR5 sequences. The WT sequence produced a normal 352-amino acid protein with the correct reading frame. In contrast, the documented CCR5 Δ32 mutation deleted 32 nucleotides, causing a frameshift and producing a shorter 343-amino acid protein with a premature stop codon. The artificial one-nucleotide deletion also caused a frameshift and changed the downstream amino acid sequence. These results show that deletions in the CCR5 coding sequence can greatly affect the structure and predicted function of the protein.

# WT versus Mutant Protein Comparison
Gene: CCR5 Reference transcript: NM_000579.3 
Reference protein: NP_000570.1

Documented variant: NM_000579.3:c.554_585del32 Protein consequence: p.Ser185fs Mutation type: Frameshift deletion

WT protein length: 352 amino acids 
Mutant protein length: 343 amino acids

WT:     HYTCSSHFPYSQYQFWKNFQTL
Mutant: HYTCSSHFPYIKDSHLGAGPAA

# Artificial Mutation Experiment
An artificial mutation was made by deleting one nucleotide (G) at position c.4 of the CCR5 coding sequence. The edited sequence was translated in Galaxy and compared with the wild-type protein. The deletion caused a frameshift, which changed the amino acid sequence after the mutation and produced a premature stop codon. This shows that even a single nucleotide deletion can greatly affect the structure and predicted function of the CCR5 protein. 

# Molecular Interpretation: Gene → Mutation → Protein → Cellular Effect → Phenotype
CCR5 gene → c.554_585del32 mutation → 32-base deletion → frameshift (p.Ser185fs) → truncated CCR5 protein → loss of normal CCR5 receptor function → reduced HIV entry into CD4⁺ T cells → decreased susceptibility to HIV infection.
The CCR5 gene normally produces a receptor found on the surface of immune cells, including CD4⁺ T cells. The CCR5 Δ32 mutation deletes 32 nucleotides, causing a frameshift that changes the amino acid sequence and creates a premature stop codon. As a result, a shorter, nonfunctional CCR5 protein is produced and is not properly expressed on the cell surface. Without a functional CCR5 receptor, many strains of HIV have difficulty entering immune cells, leading to reduced susceptibility to HIV infection in individuals who carry the mutation

# Limitations
This study was limited to a computational analysis using Galaxy and did not include laboratory experiments to verify the predicted effects of the CCR5 Δ32 mutation. The results were based on sequence translation and comparison of the wild-type, documented mutant, and artificial mutant proteins, so the actual protein activity and HIV resistance were not directly measured. In addition, only one documented mutation and one artificial mutation were analyzed, which means other CCR5 variants and genetic factors involved in HIV susceptibility were not included.

# Conclusion
The results of this study showed that the CCR5 Δ32 mutation causes a 32-base deletion that changes the reading frame and produces a shorter, truncated CCR5 protein. Compared with the wild-type sequence, both the documented mutant and the artificial mutation disrupted the normal amino acid sequence, demonstrating how frameshift mutations can greatly affect protein structure and function. Overall, the Galaxy analysis helped explain the relationship between DNA mutations, protein changes, and the molecular basis of reduced CCR5 function associated with HIV resistance.

# References
McLaren, P. J., & Fellay, J. (2021). HIV-1 and human genetic variation. Nature Reviews Genetics, 22(10), 645–657. https://doi.org/10.1038/s41576-021-00378-0

National Center for Biotechnology Information. (2026). RNA-seq aligners. ClinVar.
https://www.ncbi.nlm.nih.gov/clinvar/variation/8184/

National Center for Biotechnology Information. (2026). RNA-seq aligners (Gene ID: 1234). NCBI Gene. https://www.ncbi.nlm.nih.gov/gene/1234
