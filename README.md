# DNA_GC_content
📌 Overview
This project computes the GC content of DNA sequences from high-throughput sequencing data. The GC content represents the percentage of guanine (G) and cytosine (C) nucleotides in a DNA strand, which is useful in gene identification, species classification, and understanding DNA stability.

🔍 How It Works
- Reads FASTQ-style sequencing data, extracting only the DNA sequence lines.
- Counts occurrences of G and C nucleotides.
- Computes the GC content as a percentage of total bases.
- Ignores metadata and quality score lines in the file.

Input Data (FASTQ-like format):
@SEQ_ID  
CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCC  
+SEQ_ID  
hhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh  
@SEQ_ID  
GTGGGGGTGATGTCCACGATTACGCCGACCGGCTGG  
+SEQ_ID  
hhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh  

Output (GC Content Calculation):
GC Content: 0.68
