# Database Collection and Management

## Step 1. Data Collection

### Collect all the RSV sequences from the NCBI using "(human respiratory syncytial virus A[Organism])" and "(human respiratory syncytial virus B[Organism])"

- The NCBI database contains # 5927 sequences with the search term (human respiratory syncytial virus A[Organism]) the database contains and 3972 sequences with the search term (human respiratory syncytial virus B[Organism]).

## Step 2. Data Management

- Please remove sequences that have the text of Human respiratory syncytial virus MinA, Human respiratory syncytial virus MinB, patent, Chain, construct etc. in the title from the downloaded textfile NCBI.

- ** Meanwhile, please have and print the each gene order on genome, gene legnth, and the first 4 codons and last 4 condons of each gene on paper. These will help while working with multiple alignment file.

- Multiple alignment: 

       - Make sure to use full genome(s) as a reference or template sequence, and run the multiple alignment using "MAFFT" https://mafft.cbrc.jp/alignment/server/ - this is quick for this huge run. 
       
       - Manually review the multiple alignment and check how gene(s) are distributed with reference to template.
       
       - If everything looks OK then 1. make sure have back of main dataset, 2. using the above collected ** make gene-based files, and also whole genome file.
       
       - Data cleaning: - will discuss
       
       - collect the genbank meta-data: - Geoboost (I am working on this - will have an idea how it works) - so decide upon. or we may look for alternatives
       
       - Once have all data - will update the sequence titles and make .csv files for next step.
       
 - Descriptive statistics
       
       
