---
title: Evaluation
permalink: evaluation
---

For a detailed description of the evaluation settings please refer to the [HIPE-2022 Participation Guidelines](https://doi.org/10.5281/zenodo.6045662).


### Evaluation metrics and scorer   

The performance of systems will be evaluated in terms of Precision, Recall and F-measure (macro and micro). For NERC, two evaluation settings will be considered considered: strict (exact boundary matching) and relaxed (fuzzy boundary matching).    


The [HIPE 2020 scorer](https://github.com/impresso/CLEF-HIPE-2020-scorer) will be used again.


<span style="color:orange">**Important:**</span>  Teams **cannot use any additional data from the primary data projects** than the material available via HIPE-2022 train/sample/dev sets and released in the HIPE-2022-data repository for training their system. But they can use annotated data from any other project. The principles of trust and academic integrity apply.



### Task Bundles, Tracks and Challenges


To accommodate the different dimensions that characterize HIPE-2022 (tasks, languages, document types, entity tag sets) and foster research on transferability, the evaluation lab is organized around challenges and tracks. HIPE-2022 defines the following:

- **task bundle**:  as for CLEF-HIPE-2020, a task bundle is a predefined set of tasks. 
- **submission bundle**: a triple composed of [dataset-language-taskbundle].
- **track**: a specific triple composed of the test set of [dataset-language-task].
- **challenge**: a HIPE-2022 predefined set of tracks. A challenge can be seen as a kind of tournament with multiple tracks.

HIPE-2022 specifically evaluates 3 challenges:

**1. Multilingual Newspaper Challenge (MNC)**:    
 
The multilingual newspaper challenge aims at fostering the development of multilingual NE processing approaches on historical newspapers. 
 
* submission bundles must be composed of datasets of type “newspaper” only;
* submission bundles may be for different newspaper datasets;
* submission bundles must be for at least two languages for a same task (thus teams should submit a minimum of two submission bundles for this challenge);
* submission bundles must be for two task bundles at most, among: bundle 2, 4, 5 .
 
**2. Multilingual Classical Commentary Challenge (MCC):**

The multilingual classical commentary challenge aims at adapting NE solutions to domain-specific entities in a special DH text type.     

* submission bundles must be composed of the dataset  “ajmc” only;
* submission bundles must be for at least three languages for the same task;
* submission bundles must be for two task bundles at most, among: bundle 2, 4, 5.
   
   
**3. Global Adaptation Challenge (GAC):**

The global adaptation challenge aims at appreciating how efficiently systems can be retargeted to any language, document type and guidelines. Submitted bundles for this challenge may be the same as for Challenge 1 and 2. 

* submission bundles must be composed of datasets of both types  “ajmc” and “newspaper”;
* submission bundles must be for at least two languages for the same task;
* submission bundles must be for two task bundles at most, among: bundle 1, 2, 3, 4, 5.


![](/assets/images/HIPE2022-EvaluationSettingOverview.png)

