# SeeGULL Multilingual: a Dataset of Geo-Culturally Situated Stereotypes

This repository contains data resources for the paper "[SeeGULL Multilingual: a Dataset of Geo-Culturally Situated Stereotypes](https://aclanthology.org/2024.acl-short.75/)". This dataset contains stereotype examples that may be offensive.

## Overview
While generative multilingual models are rapidly being deployed, their safety and fairness evaluations are largely limited to resources collected in English. This is especially problematic for evaluations targeting inherently socio-cultural phenomena such as stereotyping, where it is important to build multilingual resources that reflect the stereotypes prevalent in respective language communities. However, gathering these resources, at scale, in varied languages and regions pose a significant challenge as it requires broad socio-cultural knowledge and can also be prohibitively expensive. To overcome this critical gap, we employ a recently introduced approach that couples LLM generations for scale with culturally situated validations for reliability, and build SeeGULL Multilingual, a global-scale multilingual dataset of social stereotypes, containing over 25K stereotypes, spanning 23 pairs of languages and regions they are common in, with human annotations, and demonstrate its utility in identifying gaps in model evaluations.

## Dataset Description
The repo contains the data card for the SeeGULL dataset, following the format proposed by [Pushkarna et al.](https://arxiv.org/abs/2204.01075). The data card includes details of the dataset such as intended usage, field names and meanings, annotator recruitment and payments.
The `dataset` folder contains the following 2 subfolders:
- `stereotypes`: Containing stereotypes in various languages annotated in different countries.
- `offensiveness`: Containing the offensiveness scores for each of the attributes.

Each of these subfolders contains:
- various individual files pertaining to a language and country pair
- one combined sheet containing all the data


## Citation

```
@inproceedings{bhutani-etal-2024-seegull,
    title = "{S}ee{GULL} Multilingual: a Dataset of Geo-Culturally Situated Stereotypes",
    author = "Bhutani, Mukul  and
      Robinson, Kevin  and
      Prabhakaran, Vinodkumar  and
      Dave, Shachi  and
      Dev, Sunipa",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-short.75",
    pages = "842--854",
}

```
