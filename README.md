# the_linguists at BLP-2023 Task 1: A Novel Informal Bangla Fasttext Embedding for Violence Inciting Text Detection

This repository contains the resources and findings of the paper titled "the_linguists at BLP-2023 Task 1: A Novel Informal Bangla Fasttext Embedding for Violence Inciting Text Detection". The paper was presented at the Proceedings of the First Workshop on Bangla Language Processing (BLP-2023) in EMNLP on December 2023, Singapore.

### Authors
- Md. Tariquzzaman
- Md Wasif Kader
- Audwit Anam
- Naimul Haque
- Mohsinul Kabir
- Hasan Mahmud
- Md Kamrul Hasan

### Abstract
This paper introduces a novel informal Bangla word embedding for designing a cost-efficient solution for the task “Violence Inciting Text Detection” which focuses on developing classification systems to categorize violence that can potentially incite further violent actions. We propose a semi-supervised learning approach by training an informal Bangla FastText embedding, which is further fine-tuned on lightweight models on task-specific dataset and yielded competitive results to our initial method using BanglaBERT, which secured the 7th position with an f1-score of 73.98%. We conduct extensive experiments to assess the efficiency of the proposed embedding and how well it generalizes in terms of violence classification, along with its coverage on the task’s dataset. Our proposed Bangla IFT embedding achieved a competitive macro average F1 score of 70.45%. Additionally, we provide a detailed analysis of our findings, delving into potential causes of misclassification in the detection of violence-inciting text.

### Conference Details
- **Conference Title:** Proceedings of the First Workshop on Bangla Language Processing (BLP-2023)
- **Date:** December 2023
- **Location:** Singapore
- **Publisher:** Association for Computational Linguistics
- **Pages:** 214-219
- **DOI:** [10.18653/v1/2023.banglalp-1.26](https://doi.org/10.18653/v1/2023.banglalp-1.26)

### Citation
If you find this work useful in your research, please consider citing:
```bib
@inproceedings{tariquzzaman-etal-2023-linguists,
    title = "the{\_}linguists at {BLP}-2023 Task 1: A Novel Informal {B}angla {F}asttext Embedding for Violence Inciting Text Detection",
    author = "Tariquzzaman, Md.  and
      Kader, Md Wasif  and
      Anam, Audwit  and
      Haque, Naimul  and
      Kabir, Mohsinul  and
      Mahmud, Hasan  and
      Hasan, Md Kamrul",
    editor = "Alam, Firoj  and
      Kar, Sudipta  and
      Chowdhury, Shammur Absar  and
      Sadeque, Farig  and
      Amin, Ruhul",
    booktitle = "Proceedings of the First Workshop on Bangla Language Processing (BLP-2023)",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.banglalp-1.26",
    pages = "214--219",
    abstract = "This paper introduces a novel informal Bangla word embedding for designing a cost-efficient solution for the task {``}Violence Inciting Text Detection{''} which focuses on developing classification systems to categorize violence that can potentially incite further violent actions. We propose a semi-supervised learning approach by training an informal Bangla FastText embedding, which is further fine-tuned on lightweight models on task specific dataset and yielded competitive results to our initial method using BanglaBERT, which secured the 7th position with an f1-score of 73.98{\%}. We conduct extensive experiments to assess the efficiency of the proposed embedding and how well it generalizes in terms of violence classification, along with it{'}s coverage on the task{'}s dataset. Our proposed Bangla IFT embedding achieved a competitive macro average F1 score of 70.45{\%}. Additionally, we provide a detailed analysis of our findings, delving into potential causes of misclassification in the detection of violence-inciting text.",
}
```
Embedding dataset: [kaggle](https://www.kaggle.com/datasets/mdtariquzzamanfaisal/bangla-informal-fasttext-embedding/data)

[Link to PDF](https://aclanthology.org/2023.banglalp-1.26.pdf)

### License
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
