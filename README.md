# Evolutionary Multiobjective Feature Selection for Sentiment Analysis

In this project, we present a hybrid multiobjective feature selection model for the sentiment analysis task, which harnesses the power of an entropy-based metric, i.e., Information Gain, and an evolutionary algorithm, i.e., Non-dominated Sorting Genetic Algorithm II. Experiments with different machine learning and feature extraction techniques on the well-known [Stanford Sentiment Treebank](https://nlp.stanford.edu/sentiment/) dataset demonstrated that our model improves the learning performance of the sentiment analysis task considerably.

The Jupyter Notebook file in this repository consists of the following results:

**Baseline:** Classification on the preprocessed data.

**IGF:** Classification after applying Information Gain Filtering on the preprocessed data.

**IGF+NSGA-II:** Classification after applying Information Gain Filtering followed by Non-dominated Sorting Genetic Algorithm II on the preprocessed data.


## Citation

If you find this repository useful in your research, please cite the following [paper](https://ieeexplore.ieee.org/abstract/document/9564078):


**APA format:**

> Deniz, A., Angin, M., & Angin, P. (2021). Evolutionary Multiobjective Feature Selection for Sentiment Analysis. *IEEE Access*, 9, 142982-142996.


**Bibtex format:**

```
@article{deniz2021evolutionary,
  title={Evolutionary Multiobjective Feature Selection for Sentiment Analysis},
  author={Deniz, Ay{\c{c}}a and Angin, Merih and Angin, Pelin},
  journal={IEEE Access},
  volume={9},
  pages={142982--142996},
  year={2021},
  publisher={IEEE}
}
```
