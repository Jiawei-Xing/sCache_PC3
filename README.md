# sCache_PC3
Manuscript: Chemoreceptor family in plant-associated bacteria that responds preferentially to the plant signal molecule glycerol 3-phosphate.

### PacP-alphafold.pdb
AlphaFold2 model for PacP Cache domain (default parameters).

### DiffDock_rank1_confidence-0.06.sdf
The best docking result of dihydroxyacetone phosphate by DiffDock (10 inference steps).

### PacP+DHAP.pse
PacP model with docked dihydroxyacetone phosphate visualized in PyMol.

### ECA2530-TM+Cache_msa.fa
Total 4999 aligned sequences by BLAST against RefSeq using PacP Cache as the query (E-value < 0.5).

### ECA2530-Cache_1100.fa
Ligand binding portions of top 1100 sequences from BLAST.

### ECA2530-Cache_1100_cdhit98.fa
Reducing redundancy of 1100 sequences to 610 sequences by CD-HIT (identity threshold < 0.98).

### ECA2530-Cache_1100_cdhit98.fa.clstr
610 clusters from CD-HIT.

### ECA2530-Cache_1100_cdhit98+CitA_msa.fa
Multiple sequence alignment of 610 sequences using MAFFT (default parameters). A Cache domain homolog from CitA was included for comparison but was not used for downstream analysis.

### check_R98.py
Taking the sequence alignment and the maximum likelihood tree from MEGA (default parameters), updating the presence of PacP-R105 (R98 in alignment) to the tree labels.

### ECA2530-Cache_1100_cdhit98_msa_labelR.nwk
Maximum likelihood tree with PacP-R105 labels (Arg, Lys, or other amino acids).

### cdhit.py
Taking the sCache_PC3 members from the tree, mapping to their original proteins before removed by CD-HIT.

### sCache_CP3_before.txt
All members of sCache_PC3 before CD-HIT.

### ITC data.docx
Additional ITC studies of binding of different compounds to ligand binding domains of receptors.
