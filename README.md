# PanaAtlas
A great map for ML/NLP Tools/Work in Biomedical Domain

## Language Models
| Model Name | Links to model | Tested benchmarks | Year |
| :--: | :--: | :--: | :--: |
| [BioBERT](https://arxiv.org/abs/1901.08746) | [here](https://github.com/naver/biobert-pretrained) || 2019 |
| [SciBERT](https://arxiv.org/abs/1903.10676) | [here](https://github.com/allenai/scibert) | [ChemProt](https://biocreative.bioinformatics.udel.edu/news/corpora/chemprot-corpus-biocreative-vi/)| 2019 |
| [Pretrained Language Models for Biomedical and Clinical Tasks](https://aclanthology.org/2020.clinicalnlp-1.17/) | [here](https://github.com/facebookresearch/bio-lm) | | 2020 |
| [BioMedBERT](https://aclanthology.org/2020.coling-main.59/) | [here](https://github.com/BioMedBERT/biomedbert) || 2020 |
|[BioMegatron](https://aclanthology.org/2020.emnlp-main.379/)| [here](https://catalog.ngc.nvidia.com/models?filters=&orderBy=dateModifiedDESC&query=biomegatron) || 2020 |
|[PubMedBERT](https://arxiv.org/abs/2007.15779)|[here](https://microsoft.github.io/BLURB/models.html)|| 2021 |
| [BioM-Transformers](https://aclanthology.org/2021.bionlp-1.24/) | [here](https://github.com/salrowili/BioM-Transformers) || 2021 |
|[BioLinkBERT](https://arxiv.org/abs/2203.15827)|[here](https://github.com/michiyasunaga/LinkBERT)| [BLURB](https://microsoft.github.io/BLURB/), [MedQA](https://github.com/jind11/MedQA), [MMLU](https://github.com/hendrycks/test) | 2022 |

## Datasets and Benchmarks
| Data name | Description | Paper | Year |
| :--: | :--: | :--: | :--: |
| [BC5CDR](https://biocreative.bioinformatics.udel.edu/tasks/biocreative-v/track-3-cdr/) | A benchmark for automatic extraction of mechanistic and biomarker chemical-disease relations from the biomedical literature | | 2014 |
|[MIMIC-III](https://physionet.org/content/mimiciii-demo/1.4/) | A freely accessible critical care database | [here](https://www.nature.com/articles/sdata201635#:~:text=MIMIC%2DIII%20('Medical%20Information,a%20large%20tertiary%20care%20hospital.)) | 2019 |
|[PubMed Data](https://pubmed.ncbi.nlm.nih.gov/download/) | PubMed contains citations and abstracts of biomedical literature from several resources || Last update: 2021 |
|[BigScience Initative](https://github.com/bigscience-workshop/biomedical)| A biomedical datasets hackathon to centralize NLP datasets in the biological and medical space | | 2022 |

## BioNLP Tools

| Name | Company/Developer | Description | Documentation |
| :--: | :--: | :--: | :--: |
| [SciSpaCy](https://allenai.github.io/scispacy/) | Allen Institute for AI (AI2) | Models for processing biomedical, scientific or clinical text | |
| [MedSpacy](https://github.com/medspacy/medspacy) | University of Utah | Library for clinical NLP with spaCy | [Paper](https://arxiv.org/abs/2106.07799) |
| [Stanza](https://stanfordnlp.github.io/stanza/biomed.html) | Stanford | Biomedical and clinical syntactic analysis and Named Entity Recognition (NER) models | [Demo](http://stanza.run/bio) |
|[MedCAT](https://github.com/CogStack/MedCAT)| [CogStack](https://cogstack.org/) | Extracting information from Electronic Health Records (EHRs) and link it to biomedical ontologies | [Paper](https://arxiv.org/abs/2010.01165), [Demo](https://medcat.rosalind.kcl.ac.uk/) |
| [CLAMP](https://clamp.uth.edu/) | The University of Texas Health Science Center at Houston (UTHealth) | Clinical Language Annotation, Modeling, and Processing Toolkit ||
| [Text2Mol](https://github.com/cnedwards/text2mol) | University of Illinois Urbana-Champaign (UIUC) | Cross-Modal Molecular Retrieval with Natural Language Queries | [Paper](https://aclanthology.org/2021.emnlp-main.47/) |
| [Trove](https://github.com/som-shahlab/trove) | [Center for Biomedical Informatics Research, Stanford University](https://bmir.stanford.edu/) | A research framework for building weakly supervised (bio)medical named entity recognition (NER) | [Paper](https://www.nature.com/articles/s41467-021-22328-4)|
| [BioPortal](https://bioportal.bioontology.org/)| National Center for Biomedical Ontology | A comprehensive repository of biomedical ontologies ||


## Annotation Tools

| Name | Company/Developer | Documentation |
| :--: | :--: | :--: |
| [Light Tag](https://www.lighttag.io/) | Primer.ai | |
| [prodigy](https://prodi.gy/) | Explosion.ai | |

## Papers/Tasks
* [[2022] Translation between Molecules and Natural Language](http://blender.cs.illinois.edu/paper/molt5.pdf)
    * Translation between molecules and language by presenting **MolT5** – a selfsupervised learning framework for pretraining models on a vast amount of unlabeled natural language text and molecule strings.
* [[2021] Joint Biomedical Entity and Relation Extraction with Knowledge-Enhanced Collective Inference](https://aclanthology.org/2021.acl-long.488.pdf)
    * A novel framework that utilizes external knowledge for joint biomedical entity and relation extraction named KECI (Knowledge-Enhanced Collective Inference).  
