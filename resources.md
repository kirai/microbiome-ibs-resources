# Microbiome startups

## OneCodex

Allows users to upload their data and analyze it for them: https://www.onecodex.com

## Kallotype

Brain gut axis startup: https://www.kallyope.com
Description: systems biology approach, using a highly integrated platform of cutting-edge technologies, to create a comprehensive map of gut-brain circuits

## Metagenomics analysis platform

Goverment funded 16s analysis platform: http://metagenomics.anl.gov/mgmain.html?mgpage=analysis

## Ubiome

Most used 16s rRNA DTC service: https://www.ubiome.com

## Viome

Ubiome competitor: https://www.viome.com

## Eligo Bioscience

SSAMS: Sequence-Specific Antimicrobials: https://eligo-bioscience.com/

# Open Data

- American Gut project
  -Data from Short Read Archive (NCBI SRA): https://www.ncbi.nlm.nih.gov/sra?term=ERP012803
 
- Human Microbiome project
  - Data browser: http://hmpdacc.org/resources/data_browser.php
  - Reference genome data, 3000 reference genomes isolated from human body sites
      - Gastrointestinal tract is the one with more data:
        - http://hmpdacc.org/HMRGD/
      - Most common OTUs available for download:
        - http://www.hmpdacc.org/most_wanted/

- EBI Metagenomics
  - More than 70.000 samples available for download
    https://www.ebi.ac.uk/metagenomics/projects/doSearch?search=Search&includingChildren=true&biomeLineage=root:Host-associated:Human
  - Using search filters I could find a high methane producer sample, but it was a sheep not a human :)
  - You can visualize a single subject analysis the same way as in Ubiome or MyKinso: https://www.ebi.ac.uk/metagenomics/projects/ERP000108/samples/ERS006553/runs/ERR011089/results/versions/1.0
  - We could potentially submit our data to them: http://www.ebi.ac.uk/ena/submit

- Japanese HIT Metagenome project with data of people with illnesses (Could not find IBS data):
     https://humandbs.biosciencedbc.jp/en/

- GenomeSync Database: www.genomesync.org

- Collection of Pathway/Genome Databases from the Human Gut http://www.gutcyc.org/

- Tons of data of people with IBD (Even metabolites)
  - https://ibdmdb.org/tunnel/public/summary.html

- Prediabetics 16s rRNA dataset
    http://hmp2-data.stanford.edu

- 7 samples of people with SIBO
  - http://www.ebi.ac.uk/biosamples/search?searchTerm=sibo&rows=10&start=0&useFuzzySearch=false&filters=bodyProductFilter%7CUBERON%3Afeces%2CbodySiteFilter%7CUBERON%3Afeces
  
- Ribosomal database project:
  - RDP provides quality-controlled, aligned and annotated Bacterial and Archaeal 16S rRNA sequences, and Fungal 28S rRNA sequences, and a suite of analysis tools to the scientific community. https://rdp.cme.msu.edu

- Metahit http://www.metahit.eu 
  
- My New Gut http://www.mynewgut.eu/
  
- Greengenes project, (Healthy subjects)
  It looks like a dying project but they have tons of open 16s rRNA data
  - http://greengenes.secondgenome.com/downloads

# Libraries and tools from microbial analysis:
  - QIIME based python 
    - http://phylotoast.org
    - Qiime 2: https://qiime2.org
  - Mothur: 
    - https://www.mothur.org/wiki/Main_Page , 
    - https://www.mothur.org/wiki/Classify.seqs
  - Build taxonomy from raw 16s rRNA fasta files: https://grunwaldlab.github.io/metacoder_documentation/vignettes--01--extracting_taxonomy_data.html
  - R library to do analysis of microbiological communities: https://joey711.github.io/phyloseq/
  - Silva Tree Viewer http://treeviewer.mpi-bremen.de/tree_viewer_public/#13/79.9418/0.0748
- Very cool app to track and manage wet lab experiments: http://findingsapp.com
- Metagenomics workflow standard attempt "Common Workflow Language":
    - Slides (In slides 5-7 shows a list of all the existing computational research workflow systems):  https://docs.google.com/presentation/d/1bNJo2JTE3bqv6WnWJOmvBsg_ZKDID3KjsNvtE4JrT34/edit#slide=id.p4
    - Documentation: http://www.commonwl.org/v1.0/CommandLineTool.html
- SGIDNA proprietary software: https://www.sgidna.com/archetype.html
 - Oxford Nanopore Metrichor base-calling (Cloud based) 
 - NanonetRNN Basecaller  (Local)  https://github.com/nanoporetech/nanonet
 - Poretools https://github.com/arq5x/poretools
 - Centrifuge (Classifier for metagenomic sequences) , I think this is what makes classification very fast: https://ccb.jhu.edu/software/centrifuge/manual.shtml

# FMT

## Open Biome

US based open FMT community: http://www.openbiome.org/
