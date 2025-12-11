# Psychographic traits identification based on Political Ideology: An Author Analysis Study on Spanish Politicians' tweets posted in 2020
https://www.sciencedirect.com/science/article/pii/S0167739X21004921

In general, people are usually more reluctant to follow advice and directions from politicians who are not of their ideology. In extreme cases, people can be heavily biased in favour of a political party at the same time they are in blinded disagreement with others, which makes for irrational decision making and it can put people's lives at risk by ignoring certain recommendations from the authorities. Therefore, considering political ideology as a psychographic trait can improve political micro-targeting by helping public authorities and local governments to design better communication policies during crises. In this work we explore the reliability of determining psychographic traits concerning political ideology. Our contribution is twofold. On the one hand, we release the PoliCorpus-2020, a dataset composed by Spanish politicians' tweets posted in 2020. On the other hand, we conduct two author analysis tasks with the aforementioned dataset: an author profiling task to extract demographic and psychographic traits, and an author attribution task to determine the author of an anonymous text in the political domain. Both experiments are evaluated with several neural network architectures grounded on explainable linguistic features, statistical features, and state-of-the-art transformers. In addition, we test if the neural network models can be extrapolated to detect the political ideology of non-politician citizens. Our results indicate that the linguistic features are good indicators for identifying fine-grained political affiliation, they boost the performance of neural networks models when combined with embedding-based features, and they preserve relevant information when the models are tested with citizens who are not politicians. Besides, we found that lexical and morphosyntax features are more effective on author profiling whereas stylometric features are more effective in author attribution.


## Citation
```
@article{garcia2022psychographic,
  title={Psychographic traits identification based on political ideology: An author analysis study on spanish politicians’ tweets posted in 2020},
  author={Garc{\'\i}a-D{\'\i}az, Jos{\'e} Antonio and Colomo-Palacios, Ricardo and Valencia-Garc{\'\i}a, Rafael},
  journal={Future Generation Computer Systems},
  volume={130},
  pages={59--74},
  year={2022},
  publisher={Elsevier}
}
```

## Dataset distribution
| Trait        | Class   | Total | Train | Val | Test |
|--------------|---------|-------|-------|-----|------|
| Gender       | female  | 113   | 67    | 23  | 23   |
|              | male    | 156   | 99    | 29  | 28   |
| Age          | 25-34   | 28    | 21    | 1   | 6    |
|              | 35-49   | 126   | 80    | 23  | 23   |
|              | 50-64   | 104   | 57    | 26  | 21   |
|              | over 65 | 11    | 8     | 2   | 1    |
| Spectrum     | left    | 146   | 88    | 31  | 27   |
| (binary)     | right   | 123   | 78    | 21  | 24   |
| Spectrum     | left    | 56    | 37    | 12  | 7    |
| (multiclass) | m-left  | 90    | 51    | 19  | 20   |
|              | m-right | 83    | 54    | 15  | 14   |
|              | right   | 39    | 23    | 6   | 10   |
| Spectrum     | left    | 31    | -     | -   | 31   |
| (binary)     | right   | 20    | -     | -   | 20   |
| Spectrum     | left    | 20    | -     | -   | 20   |
| (multiclass) | m-left  | 11    | -     | -   | 11   |
|              | m-right | 13    | -     | -   | 13   |
|              | right   | 7     | -     | -   | 7    |


## Install
TBD


## Folders
    ```config/``` Contains the configuration of the PoliCorpus-2020
    ```code/``` Contains the scripts
    ```assets/``` contains assets (dataset, features, models, evaluations) for each dataset
    ```embeddings/``` Contains pretrained word embeddings models
