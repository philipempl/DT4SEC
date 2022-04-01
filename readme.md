# DT4SEC: A Systematic Literature Review

> **"Like many others, we posit that more systematic and transparent reviews hold
the potential to possess more validity/credibility and to manifest improved reproducibility of methods."**
>
> -- _Guy Paré, Mary Tate, David Johnstone, Spyros Kitsiou: Contextualizing the twin concepts of systematicity and transparency in information systems literature reviews. Eur. J. Inf. Syst. 25(6): 493-508 (2016)_

## Abstract
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Research Questions
To demystify the digital twin paradigm, we aim to answer the following research questions (RQ):
- **RQ1**: What are digital twins from a cybersecurity perspective?
- **RQ2**: How do digital twins contribute to cybersecurity?
- **RQ3**: How to implement digital twins for security operations?
- **RQ4**: What are current challenges and future cybersecurity research areas enhancing digital twins?

## Contribution
By answering the research questions, we contribute to the following:
1. We demystify the security-related digital twin paradigm.
2. We illustrate the state-of-the-art in applying digital twins for cybersecurity.
3. We provide a collection of best practices and implementation details for digital twins.
4. We call attention to challenges and derive future research actions.

## 1. Search
You can find all the iterative and systematic search details in the [/search](/search) directory. This directory consists of single BibTex files containing bibliograpic entries. We searched a total of ten IS databases ([dblp](https://dblp.org/), [arXiv](https://arxiv.org/), [AISeL](https://aisel.aisnet.org/), [WoS](https://www.webofscience.com), [IEEE Xplore](https://ieeexplore.ieee.org), [ACM](https://dl.acm.org/), [CSDL](https://www.computer.org/csdl/home), [Wiley](https://onlinelibrary.wiley.com/), [Springer Link](https://link.springer.com/), [ScienceDirect](https://www.sciencedirect.com/)) and performed subsequent backward and forward searches. We merged all unique entries into the BibTex file [references.bib](references.bib).

## 2. Screen
Based on obtained results, we screened the literature. You find the details in the file [screen.csv](screen.csv) and the included entries in [/screen/included_references_count=114.bib](/screen/included_references_count=114.bib). We conducted the first screen based on the title. The second screen involves the availability of the full text applying different exclusion criteria: quality, availability, digital twins applied for non-security use cases, digital twins are not mentioned, digital twins involved in a scenario other than IoT or CPS, security enhancements for digital twins, or a complete book instead of single chapters. The application of the quality and exclusion criteria leads to the following results:


```
┌ Search
| - total: 4898
| - merged: 4397
|
├ Screen 1
| - total: 4397
| - included: 659
| - excluded: 3738
|
├ Screen 2
| - total: 659
| - included: 114
| - excluded: 468
| - TODO: 77
|
└ Result: 114
```

## 3. Extraction
We extracted relevant information from the yielded literature set in the next step. The coding is documented in [/extraction/coding.csv](/extraction/coding.csv). Thereby we defined fields of interest satisfying our pre-defined research questions.

## 4. Analysis
Last but not least, we analyze, interpret, and synthesize the extracted data using [Jupyter Notebook](https://jupyter.org). We also include some details on bibliometric data. Our entire working notebook loading the [/extraction/coding.csv](/extraction/coding.csv) file and the [/screen/included_references_count=114.bib](/screen/included_references_count=114.bib) file can be found under [/analysis](/analysis). The BibTex file is used for bibliometric analysis and the CSV file for in depth thematic analysis. The results can be reproduced by executing or clicking the notebook.

## 5. Conclusions
We summarized all the insights and concluding remarks in our paper. The manuscript can be found under [/conclusion](/conclusion).

## Reference
```
@article{Empl2022,
author = {Philip Empl and G{\"u}nther Pernul,
title = {DT4SEC: A Systematic Review on Digital Twins in the Cybersecurity Domain},
journal = {{ACM} Computing Surveys},
volume = {XX},
number = {X},
pages = {XX:1--XX:36},
year = {2022},
url = {https://doi.org/10.11XX/XXXXX},
doi = {10.11XX/XXXXX}
}
```
## Authors

- ****Philip Empl**** - [Department of Information Systems](https://www.uni-regensburg.de/wirtschaftswissenschaften/wi-pernul/team/philip-empl/index.html) **@ University of Regensburg**



