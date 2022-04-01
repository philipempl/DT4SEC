# DT4SEC: A Systematic Literature Review

> *"Like many others, we posit that more systematic and transparent reviews hold
the potential to possess more validity/credibility and to manifest improved reproducibility of methods."*
>
> -- Guy Paré, Mary Tate, David Johnstone, Spyros Kitsiou: Contextualizing the twin concepts of systematicity and transparency in information systems literature reviews. Eur. J. Inf. Syst. 25(6): 493-508 (2016)

## Abstract
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Contribution
- We demistify the security-related Digital Twin paradigm.
- We illustrate the state-of-the-art in applying digital twins for cybersecurity.
- We provide a collection of best practices and implementation details for Digital Twins.
- We call attention to challenges and derive future research actions.

## Research Questions
- What are Digital Twins from a cybersecurity perspective?
- How do Digital Twins contribute to cybersecurity?
- How to implement Digital Twins for security operations?
- What are current challenges and future research areas of cybersecurity enhancing Digital Twins?

## 1. Search
You can find all the iterative and systematic search details in the [/search](https://github.com/philipempl/DT4SEC/tree/master/search) directory. We searched a total of ten IS databases ([dblp](https://dblp.org/), [arXiv](https://arxiv.org/), [AISeL](https://aisel.aisnet.org/), [WoS](https://www.webofscience.com), [IEEE Xplore](https://ieeexplore.ieee.org), [ACM](https://dl.acm.org/), [CSDL](https://www.computer.org/csdl/home), [Wiley](https://onlinelibrary.wiley.com/), [Springer Link](https://link.springer.com/), [ScienceDirect](https://www.sciencedirect.com/)) were searched and performed subsequent backward and forward searches. 

## 2. Screen
Based on obtained results, we screened the literature. You find the details in the file [screen.csv](https://github.com/philipempl/DT4SEC/blob/master/screen.csv) and the included entries in [/screen/included_references_count=114.bib](https://github.com/philipempl/DT4SEC/blob/master/screen/included_references_count=114.bib). We conducted the first screen based on the title. The second screen involves the availability of the full text applying different exclusion criteria: quality, availability, digital twins applied for non-security use cases, digital twins are not mentioned, digital twins applied in a scenario other than IoT or CPS, security enhancements for digital twins, or a complete book instead of single chapters. This leads to the following results:


```
 ┌ Search
 |  - total:              1285
 |  - merged:             1000
 |
 ├ Screen 1
 |  - total:              4397
 |  - included:            659
 |  - excluded:           3738
 |
 ├ Screen 2
 |  - total:               659
 |  - included:            114
 |  - excluded:            468
 |  - TODO:                 77

Final set size: 114
```

## 3. Extraction
In the next step, we extracted relevant information out of the yielded literature set. The coding is documented in [/extraction/coding.xlsx](https://github.com/philipempl/DT4SEC/blob/master/extraction/coding.xlsx). Thereby we defined fields of interest satisfying our pre-defined research questions.

## 4. Analysis
Last but not least, we analyze, interpret, and synthesize the extracted data using [Jupyter Notebook](https://jupyter.org/). We also include some details on bibliometric data. Our full working notebook loading the  [/extraction/coding.xlsx](https://github.com/philipempl/DT4SEC/blob/master/extraction/coding.xlsx) file can be found under [/analysis](https://github.com/philipempl/DT4SEC/blob/master/analysis). You can reveal the results by executing or clicking on the notebook.

## 5. Conclusions
We summarized all the insights and concluding remarks in our paper. The manuscript can be found under [/conclusion](https://github.com/philipempl/DT4SEC/blob/master/conclusion).

## Reference
```
@article{Empl2022,
  author    = {Philip Empl and Günther Pernul,
  title     = {DT4SEC: A Systematic Review on  Digital Twins in the Cybersecurity Domain},
  journal   = {{ACM} Computing Surveys},
  volume    = {XX},
  number    = {X},
  pages     = {XX:1--XX:36},
  year      = {2022},
  url       = {https://doi.org/10.11XX/XXXXX},
  doi       = {10.11XX/XXXXX}
}
```
## Authors

-   **Philip Empl** - [Department of Information Systems](https://www.uni-regensburg.de/wirtschaftswissenschaften/wi-pernul/team/philip-empl/index.html)  *@ University of Regensburg*



