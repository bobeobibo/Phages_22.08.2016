Info about columns.

'AR-Phage-Annot'

IGC.AR.gene - IGC antibiotic resistance gene presumably paired with viral gene
IGC.Vir.Id - IGC viral gene presumably paired with antibiotic resistance gene
vir.id - actual viral id of IGC.Vir.Id
Annotation - Info about that viral gene name/function
Group,Order,Family,Genus - Taxonomic information extracted from viral gene annotations (might be 'unclassified')
Name.Host_info - Phage name + host name. Some host info might be in previous taxonomy columns
Best_Hit_AR0.y - Antibiotic resistance gene name
AR0_category.y - Antibiotic resistance gene description
present.in.percent.samples - % of 230 analysed samples where this particular pair is present

'AR-Phage-Annot-Samples'
This table shows how pairs are distributed within samples
Columns are same but with two additional ones:

SampleID
normalized.repr	- number of times pairs of reads aligned on same pair in a sample, divided by overall number of paired reads mapped on IGC in this sample
