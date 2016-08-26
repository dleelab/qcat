##Citing QCAT
**_QCAT: testing causality of variants using only summary association statistics_**, 
Donghyung Lee; Tim B. Bigdeli; Vladimir I. Vladimirov; Ayman H. Fanous; Silviu-Alin Bacanu; submitted.

##Acknowledgement
**This work is supported by the National Institutes of Health with grants R25DA26119, R21MH100560, R21AA022717 and P50AA022537.**

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/US-NIH-NIDA-Logo.svg/440px-US-NIH-NIDA-Logo.svg.png" height="100px">
<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/US-NIH-NIMH-Logo.svg/280px-US-NIH-NIMH-Logo.svg.png" height="100px">
<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/7/72/US-NIH-NIAAA-Logo.svg/440px-US-NIH-NIAAA-Logo.svg.png" height="100px">

##Download QCATMIX
The current release (Version 0.1.0) of QCATMIX is for a Linux user. The pre-compiled executables for other operating systems (e.g.,  Windows, MacOS) will be available soon. The latest source codes of QCAT/QCATMIX are available upon request (dustorm_at_gmail_dot_com)

|**Direct download link**|**Version**|**Release Date**|
|:---|:---|:---|
|[QCATMIX for a Linux user]()|v1.0.0|08/25/2016|

##Download Reference Panels
|**Direct download link**|**Number of Samples**|**Number of populations**|**NCBI build**|**Release Date**|**Note**|
|:---|:---|:---|:---|:---|:---|
|[1000 Genomes Phase1 Release3](https://drive.google.com/file/d/0B_9H56XID17SLWJaWjlYekxkVkU/view?usp=sharing)|1092|14|build 37 (hg19)|Nov. 23 2010|Includes chr1-chr22|

Here are the 1000 Genome population abbreviations used by QCATMIX. AFR is an abbreviation for African; AMR for admixed American; ASN for East Asian; EUR for European. 

|**Population Abbreviation**|**Number of Subjects**|**Super Population**|**Population Description**|
|:---|:---|:---|:---|
|ASW|61|AFR|African Ancestry in Southwest US|
|CEU|85|EUR|Utah residents (CEPH) with Northern and Western European ancestry|
|CHB|97|ASN|Han Chinese in Beijing, China|
|CHS|100|ASN|Southern Han Chinese|
|CLM|60|AMR|Colombian in Medellin, Colombia|
|FIN|93|EUR|Finnish in Finland|
|GBR|89|EUR|British in England and Scotlant|
|IBS|14|EUR|Iberian populations in Spain|
|JPT|89|ASN|Japanese in Tokyo, Japan|
|LWK|97|AFR|Luhya in Wenbuye, Kenya|
|MXL|66|AMR|Mexican Ancestry from Los Angeles, USA|
|PUR|55|AMR|Puerto Rican in Puerto Rico|
|TSI|98|EUR|Toscani in Italia|
|YRI|88|AFR|Yoruba in Ibadan, Nigeria|

##Options

|**Option**|**Short Flag**|**Parameter**|**Default**|**Description**|
|:---|:---|:---|:---|:---|
|--version|-v|none|none|Prints version information.|
|--help|-h|none|none|Outputs a full description of all QCAT/QCATMIX options.|
|--local|none|none|none|Execute QCAT local test.|
|--reference|-r|filename|none|The filename of the reference population data.|
|--referenceIndex|-i|filename|none|The filename of the reference population index data.|
|--referenceInfo|none|filename|none|The filename of the reference panel information.|
|--output|-o|filename|out.qcat|The filename of QCAT/QCATMIX output|
|--chromosome|-c|integer or string|1.0|Chromosome number (or chromosome number and arm, e.g., 1q, 22p)|
|--startBp|-non|decimal|none|The start position of prediction window.|
|--endBp|-non|decimal|none|The end position of prediction window.|
|--windowSize|-n|decimal|1.0|The size of the prediction window (Mb).|
|--wingSize|-m|decimal|0.5|The size of the wing padded on the left and right of the prediction window (Mb).|
|--populationWeight|-w|filename|none|The filename of the population weight data.|
