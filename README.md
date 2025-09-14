HBB GENE ANALYSIS PROJECT

What is this project?
This is a Python program that analyzes the HBB gene (the gene that makes hemoglobin - the protein in your blood that carries oxygen). I downloaded the gene sequence from NCBI and wrote code to study it.

What did I find?
After running my code on the HBB gene, I discovered:

- Gene Length: 1608 DNA letters (bases)
- GC Content: 40.17% (This means 40% of the gene is made of G and C bases)
- ORFs Found: 
  - ORF 1: 186 bases long (starts with ATGGTG)
  - ORF 2: 402 bases long (starts with ATGAAG) - This is probably the real hemoglobin code!
  - ORF 3: 33 bases long (starts with ATGTGG)
  - ORF 4: 27 bases long (starts with ATGCTG)
  - ORF 5: 171 bases long (starts with ATGGGC)

Why is this important?
The HBB gene is super important because:
- It makes hemoglobin that carries oxygen in your blood
- If this gene has mistakes (mutations), it can cause diseases like sickle cell anemia
- Understanding genes helps scientists develop medicines

How to run this project

Step 1: Install what you need
pip install biopython

Step 2: Download these files
- gc_orf_analysis.py (my Python code)
- hbb.fasta (the gene data file)

Step 3: Run the code
python gc_orf_analysis.py

Step 4: See the results!
The program will show you the same cool results I found.

Files in this project
1. gc_orf_analysis.py - The main program that does the analysis
2. hbb.fasta - The actual HBB gene sequence from human DNA
3. requirements.txt - List of needed Python packages
4. README.md - This explanation file

About me
I made this project to learn about bioinformatics (using computers to study biology). It was really fun to see how we can use programming to understand our own DNA!

Want to learn more?
NCBI Datasets: https://www.ncbi.nlm.nih.gov/datasets
HBB gene info: https://www.ncbi.nlm.nih.gov/gene/3043

This project uses data from NCBI. Science is cool!