# Digital Twins in Security Operations
## State-of-the-Art & Outlook

> **"Like many others, we posit that more systematic and transparent reviews hold
the potential to possess more validity/credibility and to manifest improved reproducibility of methods."**
>
> -- _Guy Paré, Mary Tate, David Johnstone, Spyros Kitsiou: Contextualizing the twin concepts of systematicity and transparency in information systems literature reviews. Eur. J. Inf. Syst. 25(6): 493-508 (2016)_

## Abstract
In an era of rapid technological advancements, digital twins are gaining attention in industry and research. These virtual representations of real-world entities, enabled by the Internet of Things (IoT), offer advanced simulation and analysis capabilities. Their application spans various sectors, from smart manufacturing to healthcare, highlighting their versatility. However, the rise of digital technologies has also escalated cybersecurity concerns. Historical cyberattacks underscore the urgency for enhanced security operations. In this context, digital twins represent a novel approach to cybersecurity. Industry and academic research are increasingly exploring their potential to protect their assets. Despite growing interest and applications, more comprehensive research synthesis needs to be done, particularly in security operations based on digital twins. Our paper aims to fill this gap through a structured literature review aggregating knowledge from 201 publications. We focus on defining the digital twin in cybersecurity, exploring its applications, and outlining implementations and challenges. To maintain transparency, our data is documented and is publicly available. This survey serves as a crucial guide for academic and industry stakeholders, fostering digital twins in security operations. 

## Research Questions
To demystify the digital twin paradigm, we aim to answer the following research questions (RQ):
- **RQ1**: What constitutes a digital twin within the realm of cybersecurity?
- **RQ2**: How is the digital twin harnessed to fortify cybersecurity?
- **RQ3**: How can digital twin components be instantiated?
- **RQ4**: What pivotal challenges remain unaddressed, and what promising avenues beckon for future research?

## Contribution
By answering the research questions, we contribute to the following:
1. We confirm the components of the digital twin from a cybersecurity perspective.
2. We re-define the digital twin paradigm in cybersecurity.
3. We describe the application domains and security operations based on digital twins.
4. We provide an overview of implementation techniques and tools.
5. We shapes future research directions and open issues.


## 1. Search
You can find all the iterative and systematic search details in the [/search](/search) directory. This directory consists of single BibTex files containing bibliograpic entries. We searched a total of ten IS databases ([dblp](https://dblp.org/), [arXiv](https://arxiv.org/), [AISeL](https://aisel.aisnet.org/), [WoS](https://www.webofscience.com), [IEEE Xplore](https://ieeexplore.ieee.org), [ACM](https://dl.acm.org/), [CSDL](https://www.computer.org/csdl/home), [Wiley](https://onlinelibrary.wiley.com/), [Springer Link](https://link.springer.com/), [ScienceDirect](https://www.sciencedirect.com/)) and performed subsequent backward and forward searches. We merged all unique entries into the BibTex file [references.bib](references.bib).

## 2. Screen
Based on obtained results, we screened the literature. You find the details in the file [screen.csv](screen.csv) and the included entries in [/screen/included_references_count=138.bib](/screen/included_references_count=138.bib). We conducted the first screen based on the title. The second screen involves the availability of the full text applying different exclusion criteria: quality, availability, digital twins applied for non-security use cases, digital twins are not mentioned, digital twins involved in a scenario other than IoT or CPS, security enhancements for digital twins, or a complete book instead of single chapters. The application of the quality and exclusion criteria leads to the following results:


```
┌ Search
| - total: 6428
| - merged: 5466
|
├ Screen 1
| - total: 5466
| - included: 844
| - excluded: 4622
|
├ Screen 2
| - total: 844
| - included: 201
| - excluded: 643
|
└ Result: 201
```

## 3. Extraction
We extracted relevant information from the yielded literature set in the next step. The coding is documented in [/extraction/coding.csv](/extraction/coding.csv). Thereby we defined fields of interest satisfying our pre-defined research questions.

## 4. Analysis
Last but not least, we analyze, interpret, and synthesize the extracted data using [Jupyter Notebook](https://jupyter.org). We also include some details on bibliometric data. Our entire working notebook loading the [/extraction/coding.csv](/extraction/coding.csv) file and the [/screen/included_references_count=138.bib](/screen/included_references_count=138.bib) file can be found under [/analysis](/analysis). The BibTex file is used for bibliometric analysis and the CSV file for in depth thematic analysis. The results can be reproduced by executing or clicking the notebook.

## 5. Insights
We summarized all the insights and concluding remarks in our paper. The manuscript can be found under [/insights](/insights).

## Reference
```
@article{Empl2022,
author = {Philip Empl and David Koch, and Marietheres Dietz, and G{\"u}nther Pernul,
title = {Digital Twins for Security Operations: State of the Art and Outlook},
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



