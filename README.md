# Removing_mousereads_RNAseq
The major issue of The RNAseq data  from patient derived xenofraft samples (i.e, human tissue that is engrafted in mouse) is mouse contamination.   This program removes  mouse reads and ambiguous reads  from the aligned SAM files. This program was written for the SAM files aligned with novoaligner.

The program take two input arguments ( human and mouse sam file).

The program has three outputs :

1.Human_unique reads
2. Human_hybrid reads ( comes from the human sam file)
3. Mouse_hybrid reads ( comes from the mouse sam file)




