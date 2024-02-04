# Caenorrhabditis_2
Size of Genome: 100.2 Mb (100 x 10^6 bp)
Structure: Linear DNA, 6 chromosomes 
Protein-coding genes: 20,000-25,000
Access genome sequence at https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000002985.6/



How to find amino acid sequence of the sequence:
1. Make sure the emboss and seqtk modules are loaded into your workspace:
     module load emboss
     module load seqtk
2. Use the emboss command 'transeq' to translate the sequence to its corresponding amino acid sequence:
     transeq NC_003279.8.txt NC_003279.8.trans
   
![alt text](https://github.com/snehakini6/Caenorrhabditis_2/assets/138410658/7f6e2d89-f034-4f42-bd7e-54164a0e40b6)

How to determine the GC content of the sequence:
1.  Make sure the emboss and seqtk modules are loaded into your workspace:
     module load emboss
     module load seqtk
2. Use 'infoseq' with qualifiers '-only -pgc' to see information about the sequence, to isolate information about the GC count as a percentage:
     infoseq NC_003279.8.txt -only -pgc

![alt text](https://github.com/snehakini6/Caenorrhabditis_2/assets/138410658/d2ef7287-b8b9-4696-bd22-55b11c58a4e0)

      
