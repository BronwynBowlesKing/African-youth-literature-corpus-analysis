## Research data and analysis tools for a study of African youth literature
This repository contains the research data and Jupyter notebooks used in the study entitled: "The Eyes Tell a Story": A hermenumerical study of theme and motif in African youth literature.

### Repository contents

### Corpus files (/jaylit_african_youth_literature_corpus)
- 155 plain text files containing the primary sources.

### ATLAS.ti project files (/ATLAS.ti_coding_record)
Contains the ATLAS.ti files used for manual coding of themes:
- README_Guide_to_ATLAS.ti_files.txt
- Code_book.xlsx
- Detailed_report.pdf
- JAY_Lit_corpus_analysis.atlasti
- Multi-hot_coding_record.ti.xlsx
- Theme_summary_report.xlsx

### Python notebooks
#### thematic_coding_ayl.ipynb
Includes code for calculating hermeneutic-numerical (hermenumerical) indicators of theme.

Requirement:
- combined_coding_record.xlsx
  
#### topic_modelling_ayl.ipynb
Covers natural language processing (NLP) steps using topic modelling, word frequencies and collocations. 

Requirements:
- term_filter_list_pos.csv
- jaylit_african_youth_literature_corpus files

### Acknowledgements
This research was conducted with texts published in the open-access publication *The Journal of African Youth Literature* (https://jaylit.com), which is dedicated to young African writers. Gratitude is extended to the youth authors whose creative works form this corpus.
