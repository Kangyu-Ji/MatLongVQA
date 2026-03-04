# MatLongVQA

**[Paper] Multimodal AI for interpreting and evaluating research evidence in materials science**

This is an open-ended visual question answering benchmark built from recent optoelectronics literature to evaluate how effectively large language models can interpret materials characterization data and validate scientific hypotheses across materials science domains.

## Dataset

- The dataset consists of vision and reasoning tasks that represent complexity, multimodality, and reasoning challenges, where the LLMs need to produce long-text responses to fully address the question. 
- Category A: Numerical & Text Extraction - whether LLMs can directly extract numerical values, text, and simple trends from visual data, evaluated by accuracy against author-provided annotations.
- Category B: Visual & Logical Inference - whether LLMs can derive implicit numerical values, interpret complex visual patterns (e.g., heatmaps), and compare multiple data trends through reasoning.
- Category C: Hypothesis Validation - whether LLMs can correlate experimental figures with textual claims to validate single- and multi-modal scientific hypotheses, measured by reasoning quality, comprehensiveness, and expert satisfaction.

![](https://github.com/Kangyu-Ji/MatLongVQA/blob/main/Figure/Fig1.png)

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
