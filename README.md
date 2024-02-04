# Caenorrhabditis_2
Size of Genome: 100.2 Mb (100 x 10^6 bp)
Structure: Linear DNA, 6 chromosomes, 
Protein-coding genes: 20,000-25,000



Size of genome
 Structure (such as, linear or circular, how many chromosomes, how many plasmids)
 Estimated protein-coding genes
 Where to access the genome sequence and at what coverage it was sequenced
 Any other interesting facts about the genome that turn up


How to generate the reverse complement of a sequence:
1. Load the emboss and seqtk modules into your workspace:
     module load emboss
     module load seqtk
2. Navigate to the 'GCF_000002985.6' directory:
     cd ncbi_dataset/data/GCF_000002985.6/
3. 'infoseq' to see what the genome file contains:
     infoseq GCF_000002985.6_WBcel235_genomic.fna
4. Extract one fasta sequence from the file:
     echo NC_003279.8 > GCF_000002985.6.txt
5. Extract the sequence from the larger file and store it in a new file:
     seqtk subseq GCF_000002985.6_WBcel235_genomic.fna GCF_000002985.6.txt > NC_003279.8.txt
6. Generate the reverse complement of the sequence and store it in a new file:
     revseq NC_003279.8.txt NC_003279.8.rev
   
![alt text](https://github.com/snehakini6/Caenorrhabditis_2/assets/138410658/9c898f3a-a559-468b-916d-b4abcb6cd57f)

     
