# ngsLearn

I document the materials to learn Next Generation Sequencing (NGS) and the learning path.

1. Basic command line and shell script to handle NGS data, i.e. awk, cut, paste, sed, grep.
  I will write more example for the useful command.

  An good additional exercise is here. 
  http://www.ark-genomics.org/events-online-training/counting-known-micrornas-five-easy-steps.

2. The customised NGS toolkit, including bedtools, samtools, seqtk, and tabix are then reviewed. These materials are good start point for each of the tools.
  bedtools http://quinlanlab.org/tutorials/bedtools/bedtools.html
  bioawk https://github.com/lh3/bioawk
  seqtk https://github.com/lh3/seqtk
  tabix http://www.htslib.org/doc/tabix.html
  samtools http://samtools.github.io/

3. Python for biologist

4. RNA-Seq pipeline, i.e. aligner (bowtie2), splice junction identification (Tophat2), read count, differentially expressed gene analysis and visualization.
  Read quality contorl: 
  FastQC  http://www.bioinformatics.babraham.ac.uk/projects/fastqc/
  
  Remove low quality reads
  Fastq-mcf https://expressionanalysis.github.io/ea-utils/

  Build genome index
  Bowtie2 http://bowtie-bio.sourceforge.net/bowtie2/manual.shtml
  
  Splice junction aware alignment
  Tophat2 https://ccb.jhu.edu/software/tophat/index.shtml
  
  Alignment quality control
  RSeQC   http://rseqc.sourceforge.net/
  
  Alignment visualization 
  igv     http://software.broadinstitute.org/software/igv/
  
  Estimate gene count
  HTseq   https://pypi.python.org/pypi/HTSeq
  
  Remove duplicated reads
  Picard  https://broadinstitute.github.io/picard/
  
  Differentially expressed gene identification
  EdgeR
  https://bioconductor.org/packages/release/bioc/html/edgeR.html
  
  Cufflinks
  http://cole-trapnell-lab.github.io/cufflinks/
  
A less painful installtion of the above the packages on MacOS (with root previlige) may come from conda, such as RSeQC at https://bioconda.github.io/recipes/rseqc/README.html.

5. Exome-Seq pipeline, i.e. aligner (), GATK (), 
6. Chi-Seq pipeline 
Mistakes and erorrs may exists, please do not hestitate to point them out by an email to liuzhebiosci(you know what should be put here)163.com.
