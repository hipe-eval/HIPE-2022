---
title: Tasks & Data
permalink: tasks
---

For a detailed description of the tasks and data, please refer to the [HIPE-2022 Participation Guidelines](https://doi.org/10.5281/zenodo.6045662) and check the [HIPE-2022-data repository](https://github.com/hipe-eval/HIPE-2022-data/blob/main/README.md).



## Tasks
**Task 1: Named Entity Recognition and Classification (NERC)**

  - Subtask 1.1 - 'NERC-Coarse': recognition and classification of entity mentions according to coarse-grained types (task proposed for all languages and datasets). 
  - Subtask 1.2 - 'NERC-Fine': recognition and classification of entity mentions according to fine-grained types (cf. column 2 in Table 2), plus the detection and classification of nested entities of depth 1 (task proposed for English, French and German for some datasets).

**Task 2 : Named Entity Linking (EL)**    

Linking of NE mentions to a unique referent in [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) or to a NIL node if the mention does not have a referent in the KB. The entity linking task includes two settings: with (EL only) and without (end-to-end EL) prior knowledge of mention boundaries.


## Data

HIPE-2022 data consists of **six primary NE-annotated datasets assembled and prepared for the shared task**. Primary datasets originate from several European cultural heritage projects, from HIPE organizers’ previous research project, and from the previous HIPE-2020 campaign. Some are already published, others are released for the first time for HIPE-2022.

Primary datasets are composed of historical newspapers and classical commentaries covering ca. 200 years; they feature several languages and were annotated with different entity tag sets and according to different annotation guidelines. 

HIPE-2022 team assembles and prepares these primary datasets in **HIPE-2022 release(s)**, which correspond to a single package composed of neatly structured and homogeneously formatted files. Primary datasets undergo the following preparation steps:

- conversion to the HIPE format (with correction of data inconsistencies and metadata consolidation);
- rearrangement or composition of train and dev splits.


Below is an overview table, check the **generic HIPE-2022-data [README](https://github.com/hipe-eval/HIPE-2022-data/blob/main/README.md)** for more information on format, tagging scheme and mapping, as well as the participation guidelines.

| Dataset alias | README | Document type | Languages |  Suitable for | Project | License |
|---------|---------|---------------|-----------| ---------------|---------------| ---------------|
| ajmc       | [link](documentation/README-ajmc.md)  | classical commentaries | de, fr, en | NERC-Coarse, NERC-Fine, EL | [AjMC](https://mromanello.github.io/ajax-multi-commentary/) |
| hipe2020   | [link](documentation/README-hipe2020.md)| historical newspapers | de, fr, en | NERC-Coarse, NERC-Fine, EL | [CLEF-HIPE-2020](https://impresso.github.io/CLEF-HIPE-2020)| [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)|
| letemps    | [link](documentation/README-letemps.md) | historical newspapers    | fr | NERC-Coarse, NERC-Fine | LeTemps | [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)|
| topres19th | [link](documentation/README-topres19th.md) | historical newspapers | en | NERC-Coarse, EL |[Living with Machines](https://livingwithmachines.ac.uk/) | [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)|
| newseye    | [link](documentation/README-newseye.md)|  historical newspapers | de, fi, fr, sv | NERC-Coarse, NERC-Fine, EL |  [NewsEye](https://www.newseye.eu/) |  [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)|
| sonar      | [link](documentation/README-sonar.md) | historical newspapers  | de | NERC-Coarse, EL |  [SoNAR](https://sonar.fh-potsdam.de/)  | [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)|




<!-- 

- *Subtask 1.1 - NERC Coarse-grained*: this task includes the recognition and classification of entity mentions according to coarse-grained types (Person, Location, Organisation and Product).
- *Subtask 1.2 - NERC Fine-grained*: this task includes the recognition and classification of entity mentions according to fine-grained types (cf. column 2 in Table 2), plus the detection and classification of nested entities of depth 1, as well as entity mention components.

**Task 2 : Named Entity Linking (EL)**

This task includes the linking of named entity mentions to a unique referent in a knowledge base (KB) or to a NIL node if the mention does not have a referent in the KB. The chosen KB is [Wikidata](https://wikidata.org). 


The entity linking task includes two settings: with and without prior knowledge of mention boundaries. Concretely speaking, the [evaluation period](dates.html) will consist of two consecutive rounds, where a first NEL task without prior information on mentions will be evaluated during round 1 (i.e. task bundles 1 and 2), and a second one with information on mention boundaries (but no type) during the second round (bundle 5).



### Detailed description

For a detailed description of the tasks and instructions relative to participation, download the **[HIPE - Shared Task Participation Guidelines](https://zenodo.org/record/3604238).**



### Task bundles

![](images/pages/bundles.png)
-->
