# MatLongVQA

**[Paper] Multimodal AI for interpreting and evaluating research evidence in materials science**

This is an open-ended visual question answering benchmark built from recent optoelectronics literature to evaluate how effectively large language models can interpret materials characterization data and validate scientific hypotheses across materials science domains.

## Dataset

- The dataset consists of vision and reasoning tasks that represent complexity, multimodality, and reasoning challenges, where the LLMs need to produce long-text responses to fully address the question. 
- Category A evaluates whether LLMs can directly extract numerical values or text and recognize trends from visual data, with performance measured by accuracy against author-provided annotations.
- Category B assesses whether LLMs can perform logical and visual inference from figures and context, including deriving implicit values, interpreting complex visual cues, and comparing trends across datasets.
- Category C tests whether LLMs can correlate experimental figures with textual claims to validate single- or multi-modal scientific hypotheses, evaluated using logical reasoning, comprehensiveness, and expert satisfaction metrics.

![alt text](https://github.com/Kangyu-Ji/MatLongVQA/blob/main/Figure/Fig1.png?raw=true)

## Software dependencies
- Python 3.13.0, then pip install the following package
- scipy https://scipy.org/
- sklearn https://scikit-learn.org/
- statsmodels https://www.statsmodels.org/
- pandas https://pandas.pydata.org/
- pingouin https://pingouin-stats.org/

## License
- This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://licensebuttons.net/l/by/4.0/88x31.png
