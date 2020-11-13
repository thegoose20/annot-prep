# Annotation Preparation

License: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

### The *DatasetExports* Folder

**Description:**
The folder includes metadata descriptions extracted from the Centre for Research Collections' online archival catalog using OAI-PMH EAD harvesting.  Metadata descriptions were extracted from four metadata fields: an identifier (<unitid>), Biographical / Historical (<bioghist>), Scope and Contents (<scopecontent>), and Processing Information (<processinfo>).  The descriptions were extracted in October 2020.  The dataset includes five files that will be annotated for instances of gender bias, in an effort to create a gold standard dataset on which an algorithm can be trained to identify and classify gender bias in text.

**Data Details:**
* Date Extracted: October 2020
* Dataset Publisher: Centre for Research Collections, University of Edinburgh
* Source: https://archives.collections.ed.ac.uk/
* Dataset Creator: Lucy Havens
* Earliest written metadata description date: Unknown (could date back to the founding of the Centre for Research Collections)
* Latest written metadata description date: 2020

**File Descriptions:**
* UoEArchivesMetadata_ID-SC-BH-PI_blindtestset.txt: descriptions from 197 collections ("fonds") that will be used to test a classification algorithm
* UoEArchivesMetadata_ID-SC-BH-PI_devset.txt: descriptions from 197 collections ("fonds") that will be used to iteratively refine a classification algorithm
* UoEArchivesMetadata_ID-SC-BH-PI_trainingset1.txt: descriptions from 197 collections ("fonds") that will be used to train a classification algorithm
* UoEArchivesMetadata_ID-SC-BH-PI_trainingset2.txt: descriptions from 197 collections ("fonds") that will be used to train a classification algorithm
* UoEArchivesMetadata_ID-SC-BH-PI_trainingset3.txt: descriptions from 195 collections ("fonds") that will be used to train a classification algorithm
