# Biomedical and Clinical NLP Atlas
A great map for ML/NLP Tools/Works in Biomedical and Clinical Domains

## Language Models
| Model Name | Model | Pretraining Data | Benchmarks | Fine-tuned Tasks | Year |
| :--: | :--: | :--: | :--: | :--: | :--: |
| [BioBERT](https://arxiv.org/abs/1901.08746) | [Here](https://github.com/naver/biobert-pretrained) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [PubMed Central® (PMC)](https://www.ncbi.nlm.nih.gov/pmc/) | | NER, Relation Extraction, Question Answering (QA) | 2019 |
| [SciBERT](https://arxiv.org/abs/1903.10676) | [Here](https://github.com/allenai/scibert) | [Semantic Scholar](https://www.semanticscholar.org/) | [ChemProt](https://biocreative.bioinformatics.udel.edu/news/corpora/chemprot-corpus-biocreative-vi/)| NER, PICO Extraction, Text Classification, Relation Classification, Dependency Parsing | 2019 |
| [ClinicalBERT](https://aclanthology.org/W19-1909/) | [Here](https://github.com/EmilyAlsentzer/clinicalBERT) [[HF Hub]](https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT) | [MIMIC-III](https://www.nature.com/articles/sdata201635) | | NER, Natural Language Inference (NLI) | 2019 |
| [BlueBERT](https://arxiv.org/abs/1906.05474) | [Here](https://github.com/ncbi-nlp/bluebert) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [MIMIC-III](https://www.nature.com/articles/sdata201635) | [BLUE](https://github.com/ncbi-nlp/BLUE_Benchmark)&nbsp;:white_check_mark: | Sentece Similarity, NER, Relation Extraction, Document Classification, NLI | 2019 |
| [BioMed-RoBERTa](https://aclanthology.org/2020.acl-main.740.pdf) | [Here](https://github.com/allenai/dont-stop-pretraining) [[HF Hub]](https://huggingface.co/allenai/biomed_roberta_base) | [S2ORC](https://github.com/allenai/s2orc) || Relation Classification,  Sequential Sentence Classification | 2020 |
| [BioALBERT](https://arxiv.org/pdf/2009.09223.pdf) | [Here](https://github.com/usmaann/BioALBERT) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [PubMed Central® (PMC)](https://www.ncbi.nlm.nih.gov/pmc/) | | NER | 2020 |
| [Pretrained Language Models for Biomedical and Clinical Tasks](https://aclanthology.org/2020.clinicalnlp-1.17/) | [Here](https://github.com/facebookresearch/bio-lm) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [PubMed Central® (PMC)](https://www.ncbi.nlm.nih.gov/pmc/), [MIMIC-III](https://www.nature.com/articles/sdata201635) | | Sequence Labelling (e.g., NER), Classification  (e.g., NLI) | 2020 |
| [BioMedBERT](https://aclanthology.org/2020.coling-main.59/) | [Here](https://github.com/BioMedBERT/biomedbert) | [BREATHE](https://console.cloud.google.com/marketplace/product/breathe-gcp-public-data/breathe?_ga=2.94363933.-1600294044.1656002794&pli=1&project=iddp-334714) | | NER, Relation Extraction, QA | 2020 |
|[BioMegatron](https://aclanthology.org/2020.emnlp-main.379/)| [Here](https://catalog.ngc.nvidia.com/models?filters=&orderBy=dateModifiedDESC&query=biomegatron) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [PubMed Central® (PMC)](https://www.ncbi.nlm.nih.gov/pmc/) | | NER, Relation Extraction, QA | 2020 |
| [BioELECTRA](https://aclanthology.org/2021.bionlp-1.16/) | [Here](https://github.com/kamalkraj/BioELECTRA) |||| 2021 |
|[PubMedBERT](https://arxiv.org/abs/2007.15779)|[Here](https://microsoft.github.io/BLURB/models.html) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/) | | NER, PICO, Relation Extraction, Sentence Similarity, Document Classification, QA | 2021 |
| [BioM-Transformers](https://aclanthology.org/2021.bionlp-1.24/) | [Here](https://github.com/salrowili/BioM-Transformers) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/), [PubMed Central® (PMC)](https://www.ncbi.nlm.nih.gov/pmc/) | | NER, Relation Extraction, QA | 2021 |
|[BioLinkBERT](https://arxiv.org/abs/2203.15827)|[Here](https://github.com/michiyasunaga/LinkBERT) [[blog]](http://ai.stanford.edu/blog/linkbert/) | [PubMed abstracts](https://pubmed.ncbi.nlm.nih.gov/) | [BLURB](https://microsoft.github.io/BLURB/), [MedQA](https://github.com/jind11/MedQA), [MMLU](https://github.com/hendrycks/test) | NER, PICO, Relation Extraction, Sentence Similarity, Document Classification, QA | 2022 |
| [Clinical-Longformer](https://arxiv.org/abs/2201.11838) | [Here](https://github.com/luoyuanlab/Clinical-Longformer) [[HF Hub]](https://huggingface.co/yikuan8/Clinical-Longformer) | [MIMIC-III](https://www.nature.com/articles/sdata201635) | [emrQA](https://github.com/panushri25/emrQA) | NER, QA, Document Classification, NLI | 2022 |
| [GatorTron](https://www.medrxiv.org/content/medrxiv/early/2022/03/18/2022.02.27.22271257.full.pdf) || [UF Health Integrated Data Repository (IDR)](https://www.ctsi.ufl.edu/research/study-design-and-analysis/integrated-data-repository/), PubMed, Wikipedia, MIMIC-III || Clinical Concept Extraction, Relation Extraction, Semantic Similarity, NLI, QA | 2022 |
| [BioGPT](https://arxiv.org/abs/2210.10341) | [Here](https://github.com/microsoft/BioGPT) ||| Relation Extraction, QA, Document Classification | 2022 |
| [PubMedGPT 2.7B](https://crfm.stanford.edu/2022/12/15/pubmedgpt.html) | [Here](https://huggingface.co/stanford-crfm/pubmedgpt), [Code](https://github.com/stanford-crfm/pubmedgpt), [blog](https://www.mosaicml.com/blog/introducing-pubmed-gpt) | PubMed Abstracts and PubMed Central portions of the [Pile](https://pile.eleuther.ai/) dataset | [MedQA](https://github.com/jind11/MedQA), [PubMedQA](https://pubmedqa.github.io/), [BioASQ](http://bioasq.org/) | QA | 2022 |
| [DRAGON](https://arxiv.org/abs/2210.09338) | [Here](https://github.com/michiyasunaga/dragon) |||| 2022 |

:white_check_mark: &nbsp; Known as the first attempt to create an NLP benchmark in the biomedical domain.

➡️ &nbsp; PICO is a sequence labeling task where the model extracts spans describing the Participants (Population), Interventions, Comparisons, and Outcomes in a clinical trial paper.

➡️ &nbsp;  Sequential Sentence Classification: Each sentence of a PubMed abstract is labeled with one of the following classes: background, objective, method, result, or conclusion.

## Datasets and Benchmarks
| Data name | Description | Paper | Year |
| :--: | :--: | :--: | :--: |
| [Clinical Abbreviation Sense Inventory (CASI)](https://conservancy.umn.edu/handle/11299/137703) | A collection of clinical abbreviations and acronyms (short forms) with their possible senses (long forms) || 2012 |
| [BC5CDR (BioCreative V)](https://biocreative.bioinformatics.udel.edu/tasks/biocreative-v/track-3-cdr/) | A benchmark for automatic extraction of mechanistic and biomarker chemical-disease relations from the biomedical literature | | 2014 |
| [PubMed 200k RCT](https://github.com/Franck-Dernoncourt/pubmed-rct) | A Dataset for Sequential Sentence Classification in Medical Abstracts | [Here](https://aclanthology.org/I17-2052.pdf) | 2017 |
| [SNOMEDCT](https://bioportal.bioontology.org/ontologies/SCTO/?p=summary) | Standard Ontology Based on the Ontology for General Medical Science || 2017 |
| [MedNLI](https://github.com/jgc128/mednli) | A Natural Language Inference Dataset For The Clinical Domain | [Here](https://arxiv.org/abs/1808.06752) | 2018 |
| [EBM-NLP corpus](https://ebm-nlp.herokuapp.com/) | A corpus of 5,000 richly annotated abstracts of medical articles with PICO annotation | [Here](https://aclanthology.org/P18-1019/) | 2018 |
| [MedicationQA](https://github.com/abachaa/Medication_QA_MedInfo2019) | A gold standard corpus for Medication Question Answering | [Here](https://ebooks.iospress.nl/publication/51941) | 2019 |
| [PubMedQA](https://pubmedqa.github.io/) | A Dataset for Biomedical Research Question Answering | [Here](https://arxiv.org/abs/1909.06146) | 2019 |
|[MIMIC-III](https://physionet.org/content/mimiciii-demo/1.4/) | A freely accessible critical care database | [Here](https://www.nature.com/articles/sdata201635#:~:text=MIMIC%2DIII%20('Medical%20Information,a%20large%20tertiary%20care%20hospital.)) | 2019 |
| [MedQuAD](https://github.com/abachaa/MedQuAD) | Medical Question Answering Dataset of 47,457 QA pairs | [Here](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3119-4) | 2019 |
| [MeQSum](https://github.com/abachaa/MeQSum) | Corpus of 1,000 summarized consumer health questions | [Here](https://aclanthology.org/P19-1215/) | 2019 |
| [MedDialog](https://github.com/UCSD-AI4H/Medical-Dialogue-System) | A Chinese medical dialogue dataset | [Here](https://aclanthology.org/2020.emnlp-main.743/)| 2020 |
|[PubMed Data](https://pubmed.ncbi.nlm.nih.gov/download/) | PubMed contains citations and abstracts of biomedical literature from several resources || Last update: 2021 |
| [BLURB](https://microsoft.github.io/BLURB/) | Biomedical Language Understanding and Reasoning Benchmark | [Here](https://arxiv.org/abs/2007.15779) | Last update: 2021 |
| [BioLeaflets](https://github.com/bayer-science-for-a-better-life/data2text-bioleaflets) | A biomedical dataset for Data2Text generation | [Here](https://aclanthology.org/2021.inlg-1.40/) | 2021 |
| [MS2](https://github.com/allenai/mslr-shared-task#dataset-access) | A dataset for Multi-Document Summarization of Medical Studies ([Shared task](https://github.com/allenai/mslr-shared-task)) | [Here](https://arxiv.org/abs/2104.06486) | 2021 |
|[BigScience Initative](https://github.com/bigscience-workshop/biomedical)| A biomedical datasets hackathon to centralize NLP datasets in the biological and medical space | | 2022 |
| [CBLUE](https://github.com/cbluebenchmark/cblue) | A Chinese Biomedical Language Understanding Evaluation Benchmark | [Here](https://aclanthology.org/2022.acl-long.544/) | 2022 |
| [Unified Medical Language System (UMLS)](https://www.nlm.nih.gov/research/umls/index.html) | A set of files and software that brings together many health and biomedical vocabularies and standards to enable interoperability between computer systems. |||
| [BREATHE](https://console.cloud.google.com/marketplace/product/breathe-gcp-public-data/breathe?_ga=2.94363933.-1600294044.1656002794&pli=1&project=iddp-334714) | A large-scale biomedical database containing entries from 10 major repositories of biomedical research |||
| [BioASQ](http://bioasq.org/) | Biomedical semantic indexing and Question Answering (QA) challenges |||
| [i2b2](https://www.i2b2.org/NLP/DataSets/) | Shared Tasks for Challenges in NLP for Clinical Data |||
| [USMLE®](https://www.nbme.org/services/data-sharing) | A Clinical Skills Patient Note Corpus | [Here](https://aclanthology.org/2022.naacl-main.208.pdf) | 2022 |
| [MedMCQA](https://medmcqa.github.io/) | Multi-Subject Multi-Choice Dataset for Medical domain | [Here](https://proceedings.mlr.press/v174/pal22a.html) | 2022 |
| [eICU Collaborative Research Database (eICU-CRD)](https://eicu-crd.mit.edu/) | A database comprises of 200,859 stays at ICUs and step-down units across 208 hospitals in the continental United States |||

## BioNLP Tools

| Name | Company/Developer | Description | Documentation |
| :--: | :--: | :--: | :--: |
| [HunFlair](https://github.com/flairNLP/flair/blob/master/resources/docs/HUNFLAIR.md#comparison-to-other-biomedical-ner-tools) | [flair](https://github.com/flairNLP/flair) | A state-of-the-art NER tagger for biomedical texts ||
| [SciSpaCy](https://allenai.github.io/scispacy/) | Allen Institute for AI (AI2) | Models for processing biomedical, scientific or clinical text | |
| [MedSpacy](https://github.com/medspacy/medspacy) | University of Utah | Library for clinical NLP with spaCy | [Paper](https://arxiv.org/abs/2106.07799) |
| [Stanza](https://stanfordnlp.github.io/stanza/biomed.html) | Stanford | Biomedical and clinical syntactic analysis and Named Entity Recognition (NER) models | [Demo](http://stanza.run/bio) |
|[MedCAT](https://github.com/CogStack/MedCAT)| [CogStack](https://cogstack.org/) | Extracting information from Electronic Health Records (EHRs) and link it to biomedical ontologies | [Paper](https://arxiv.org/abs/2010.01165), [Demo](https://medcat.rosalind.kcl.ac.uk/) |
| [CLAMP](https://clamp.uth.edu/) | The University of Texas Health Science Center at Houston (UTHealth) | Clinical Language Annotation, Modeling, and Processing Toolkit ||
| [Text2Mol](https://github.com/cnedwards/text2mol) | University of Illinois Urbana-Champaign (UIUC) | Cross-Modal Molecular Retrieval with Natural Language Queries | [Paper](https://aclanthology.org/2021.emnlp-main.47/) |
| [Trove](https://github.com/som-shahlab/trove) | [Center for Biomedical Informatics Research, Stanford University](https://bmir.stanford.edu/) | A research framework for building weakly supervised (bio)medical named entity recognition (NER) | [Paper](https://www.nature.com/articles/s41467-021-22328-4)|
| [BioPortal](https://bioportal.bioontology.org/)| National Center for Biomedical Ontology | A comprehensive repository of biomedical ontologies ||
| [cTAKES™](https://ctakes.apache.org/) | Initially by [Mayo Clinic](https://www.mayoclinic.org/) | A natural language processing system for extraction of information from electronic medical record clinical free-text | [Paper](https://pubmed.ncbi.nlm.nih.gov/20819853/) |
| [Amazon Comprehend Medical](https://aws.amazon.com/comprehend/medical/) | Amazon | A tool for extracting information from unstructured medical text accurately and quickly | [Guide](https://docs.aws.amazon.com/comprehend-medical/latest/dev/compmed-dev.pdf#comprehendmedical-welcome) |
| [HITEx](https://www.i2b2.org/software/projects/hitex/hitex_manual.html#about) | Brigham and Women's Hospital and Harvard Medical School | A Health Information Text Extraction open-source natural language processing (NLP) software application | [Manual](https://www.i2b2.org/software/projects/hitex/hitex_manual.html#about) |
| [MetaMap](https://lhncbc.nlm.nih.gov/ii/tools/MetaMap.html) | Dr. Alan (Lan) Aronson at the National Library of Medicine (NLM) | A Tool For Recognizing UMLS Concepts in Text | [Here](https://lhncbc.nlm.nih.gov/ii/tools/MetaMap.html) |
| [BERN](https://bern.korea.ac.kr/) | Korea University, Seoul | A Neural Named Entity Recognition and Multi-Type Normalization Tool for Biomedical Text Mining | [Paper](https://ieeexplore.ieee.org/document/8730332) |
| [DisGeNET](https://www.disgenet.org/home/) | [Integrative Biomedical Informatics Group ](http://grib.imim.es/research/integrative-biomedical-informatics/) | A discovery platform containing one of the largest publicly available collections of genes and variants associated to human diseases | [Here](https://www.disgenet.org/dbinfo)|
| [DISNET](https://disnet.ctb.upm.es/) | [Centro de Tecnología Biomédica (CTB)](http://www.ctb.upm.es/) | A platform for drug repositioning and disease understanding through complex networks creation and analysis ||
| [BioSpaCy](https://github.com/wjbmattingly/biospacy) || A pipeline for processing biology texts ||


## Annotation Tools

| Name | Company/Developer | Documentation |
| :--: | :--: | :--: |
| [Light Tag](https://www.lighttag.io/) | Primer.ai | |
| [prodigy](https://prodi.gy/) | Explosion.ai | |

➡️ &nbsp;  [Map of Applications for Linguistic Annotation](https://lgessler.com/mala/)

## Tasks
Inspired by efforts such as [allenai/natural-instructions](https://github.com/allenai/natural-instructions), we created a list of biomedical and clinical NLP tasks. We list input and output formats, task descriptions, and some examples for each task.

## Papers
* [An updated list of Clinical NLP tasks: [Here](https://git.doit.wisc.edu/YGAO/public-available-clinical-nlp-tasks)]
* [[2022] Large Language Models Encode Clinical Knowledge](https://arxiv.org/abs/2212.13138)
* [[2022] Medical Question Understanding and Answering with Knowledge Grounding and Semantic Self-Supervision](https://arxiv.org/abs/2209.15301)
    * [Code](https://github.com/KhalilMrini/Medical-Question-Answering)
* [[2022] Large Language Models are Zero-Shot Clinical Information Extractors](https://arxiv.org/abs/2205.12689)
    * Showing that large language models, such as GPT-3, perform well at zero-shot information extraction from clinical text despite not being trained specifically for the clinical domain.
* [[2022] Making the Most of Text Semantics to Improve Biomedical Vision-Language Processing](https://www.microsoft.com/en-us/research/publication/making-the-most-of-text-semantics-to-improve-biomedical-vision-language-processing/)
    * A language model that achieves state-of-the-art results in radiology natural language inference through its improved vocabulary and novel language pretraining objective leveraging semantics and discourse characteristics in radiology reports.
* [[2022] User-Driven Research of Medical Note Generation Software (Best paper on human-centered NLP special theme Award NAACL 2022)](https://arxiv.org/pdf/2205.02549.pdf)
    * Presenting three rounds of user studies, carried out in the context of developing a medical note generation system.
* [[2022] Literature-Augmented Clinical Outcome Prediction](https://arxiv.org/abs/2111.08374#:~:text=Predictive%20models%20for%20medical%20outcomes,signals%20into%20an%20outcome%20prediction.)
    * Introducing BEEP (Biomedical Evidence-Enhanced Predictions), a novel approach for clinical outcome prediction that retrieves patient-specific medical literature and incorporates it into predictive models.
* [[2022] Translation between Molecules and Natural Language](http://blender.cs.illinois.edu/paper/molt5.pdf)
    * Translation between molecules and language by presenting **MolT5** – a selfsupervised learning framework for pretraining models on a vast amount of unlabeled natural language text and molecule strings.
* [[2021] Joint Biomedical Entity and Relation Extraction with Knowledge-Enhanced Collective Inference](https://aclanthology.org/2021.acl-long.488.pdf)
    * A novel framework that utilizes external knowledge for joint biomedical entity and relation extraction named KECI (Knowledge-Enhanced Collective Inference).

* [[2020] Infusing Disease Knowledge into BERT for Health Question Answering, Medical Inference and Disease Name Recognition](https://aclanthology.org/2020.emnlp-main.372.pdf)
    * A new disease knowledge infusion training procedure and evaluating it on a suite of BERT models including BERT, BioBERT, SciBERT, ClinicalBERT, BlueBERT, and ALBERT over three tasks and showing that these models can be enhanced in nearly all cases, demonstrating the viability of disease knowledge infusion.

* [[2018] Identifying and characterizing highly similar notes in big clinical note datasets](https://www.sciencedirect.com/science/article/pii/S153204641830073X)
    * Using a scalable algorithm to de-duplicate clinical notes and further characterize the sources of duplication.
