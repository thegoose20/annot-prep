# Annotation Preparation

License: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

### The *.ipynb* Files

**Description:** Jupyter Notebooks for harvesting, transforming and analysing text of metadata descriptions from the Centre for Research Collections online archival catalog, ArchivesSpace, prior to manual annotation.  Metadata field names include: an identifier (`<unitid>`), Title (`<title>`) Biographical / Historical (`<bioghist>`), Scope and Contents (`<scopecontent>`), and Processing Information (`<processinfo>`).

[Click here](https://mybinder.org/v2/gh/thegoose20/annot-prep/7be06f89cc3ce54a3f50714ddf8945bc20ac70da) to run the Jupyter Notebooks in MyBinder.

### The *data_to_ann.zip* Directory

**Description:** Plaintext files that will be uploaded to brat, a web-based annotation tool, for sentence-level gendered language labeling by five annotators.

**Source Information:**
* Date Extracted: October 2020
* Dataset Publisher: Centre for Research Collections, University of Edinburgh
* Source: https://archives.collections.ed.ac.uk/
* Dataset Creator: Lucy Havens
* Earliest written metadata description date: Unknown (could date back to the founding of the Centre for Research Collections)
* Latest written metadata description date: 2020

**Summary Statistics:**

*Estimates calculated using Natural Language Toolkit's (NLTK) `word_tokenize` and `sent_tokenize`*
* Characters: 13,739,019
* Tokens: 2,754,044
* Words with Metadata Field Names: 2,006,380
* Words without Metadata Field Names: 1,273,237
* Sentences: 156,124
* TXT Files: 3,649
* Fonds (archival collections): 1,081

*There will be one ANN file per TXT file with annotation labels, totalling 7,298 files*

### The CRC_units-grouped-by-fonds.csv File
**Description:** Additional metadata fields for every fonds in the data_to_ann.zip directory (1,081 rows total, one row per fonds), with six columns for:
  * String of fonds-level identifiers (highest level of the archival hierarchy)
  * List of unit identifiers (at the series, sub-series, and item (lowest level of the archival hierarchy) levels)
  * List of unit dates
  * List of units' associated geographic locations
  * List of units' associated languages
