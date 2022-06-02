###########################################################
# Author: Stephanie de Wit
# Date: 24 April, 2022
###########################################################

## README for folder '~/daur2/data_raw/Data02_rnaseq_ipsc'.

The raw FASTQ, FASTQC, alignment and count table data used in the formative assignment have not been downloaded but can be found under '/home/daur2/rnaseq/rnaseq_ipsc/'.

Run,Assay Type,AvgSpotLen,Bases,BioProject,BioSample,Bytes,Cell_line,Cell_type,Center Name,Consent,DATASTORE filetype,DATASTORE provider,DATASTORE region,Experiment,GEO_Accession (exp),Instrument,LibraryLayout,LibrarySelection,LibrarySource,Organism,Platform,ReleaseDate,Sample Name,source_name,SRA Study
SRR7866687,RNA-Seq,84,3100625705,PRJNA491516,SAMN10079885,1380751688,Fibroblast line 1 (CL1500023),Skin derived fibroblast,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705867,GSM3393001,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393001,Fibroblast line 1,SRP161949
SRR7866688,RNA-Seq,85,2678322059,PRJNA491516,SAMN10079883,1005565315,Fibroblast line 1 (CL1500023),Skin derived fibroblast,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705868,GSM3393002,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393002,Fibroblast line 1,SRP161949
SRR7866689,RNA-Seq,85,1617791810,PRJNA491516,SAMN10079882,705929729,Fibroblast line 2 (CL1500024),Skin derived fibroblast,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705869,GSM3393003,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393003,Fibroblast line 2,SRP161949
SRR7866690,RNA-Seq,85,2335911220,PRJNA491516,SAMN10079881,876704451,Fibroblast line 2 (CL1500024),Skin derived fibroblast,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705870,GSM3393004,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393004,Fibroblast line 2,SRP161949
SRR7866691,RNA-Seq,84,2388288424,PRJNA491516,SAMN10079879,1052227406,"iPSC line 1 (IPS1500030/C2\, derived from CL1500023)",iPSC,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705871,GSM3393005,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393005,iPSC line 1,SRP161949
SRR7866692,RNA-Seq,85,2538209760,PRJNA491516,SAMN10079878,954131990,"iPSC line 1 (IPS1500030/C2\, derived from CL1500023)",iPSC,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705872,GSM3393006,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393006,iPSC line 1,SRP161949
SRR7866693,RNA-Seq,85,1452793492,PRJNA491516,SAMN10079876,647030445,"iPSC line 2 (IPS1500024/293\, derived from CL1500024)",iPSC,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705873,GSM3393007,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393007,iPSC line 2,SRP161949
SRR7866694,RNA-Seq,85,1102004504,PRJNA491516,SAMN10079875,419226920,"iPSC line 2 (IPS1500024/293\, derived from CL1500024)",iPSC,GEO,public,"fastq,sra","gs,ncbi,s3","gs.US,ncbi.public,s3.us-east-1",SRX4705874,GSM3393008,NextSeq 500,PAIRED,cDNA,TRANSCRIPTOMIC,Homo sapiens,ILLUMINA,2019-04-05T00:00:00Z,GSM3393008,iPSC line 2,SRP161949

What should be here:
* general information
  + title
  + information about the authors (name, institution, email address)
  + date of data collection
  + location of data collection
* license information
* a data log with for each data file:
  + short description
  + date the file was created
  + variable list (full names and explanations)
  + units of measurements
  + definition for missing data (NA)
* methodological information
  + description of methods (you can link to piublications or protocols)
  + description of data processing (link to RMarkdown file)
  + any software or specific instruments used
  + describe details that may influence reuse or replication efforts