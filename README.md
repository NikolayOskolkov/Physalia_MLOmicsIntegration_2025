![](course_logo.jpg)

# Machine Learning for Multi-Omics Integration

## Instructor

- Dr. Nikolay Oskolkov, Lund University, NBIS SciLifeLab

## Course overview
Next-Generation Sequencing (NGS) technologies have led to the generation of vast amounts of biological and biomedical Big Data. The rapidly expanding volume and diversity of this data present both exciting opportunities and considerable challenges for analysis. Biological Big Data from various sources, often referred to as Multi-Omics data, hold great promise due to their synergistic effects, which can potentially model the behavior of biological cells. By integrating Omics data, we can uncover novel biological pathways that may not be detectable in individual Omics datasets alone. In this course, we will explore machine learning methods for integrating large biological datasets, combining both lectures and hands-on sessions.

## Target audience and assumed background
We assume some basic awareness of UNIX environment, as well as at least beginner level of R and / or Python programming.

## Learning outcomes
By completing this course, you will:

- Understand the basics of machine learning approaches to biological data analysis
- Gain an overview of bioinformatic tools and best practices for integrative Omics analysis
- Be able to design an integrative project and implement appropriate analysis methodologies
- Be able to choose the right tools and approaches to answer your specific research question
- Gain confidence in learning new methods needed to answer your research question

---

# Schedule

## Before the course

| Time   | Activity                                                          | Link                                                                                                                                                    |
|--------|-------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| ~ 1 h  | Recorded talk: Omics Logic Symposium 2022                                                                                 | [Video](https://www.youtube.com/watch?v=Jrz6t3fbOCw)                                            |
| ~ 2 h  | Primer article: Predicting type 2 diabetes via machine learning integration of multiple omics from human pancreatic islets| [PDF](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/articles/Multi_Omics_T2D_ScientificReports2024.pdf)                                                                                                                                                                                             |
| ~ 1 h  | In case needed: Recap on Unix                                                                                             | [Lab](command-line-basics.md)                                                                   |
| ~ 1 h  | Useful reading: Select features or Omics integration                                                                      | [Blog](https://medium.com/data-science/select-features-for-omics-integration-511390b7e7fd?sk=bf0c744caa41ec0cf37577d85a132276)                                                                                                                                                                                                   |
| ~ 1 h  | Useful reading: Supervised Omics integration                                                                              | [Blog](https://medium.com/data-science/supervised-omics-integration-2158e1a6d23f?sk=6e4e6fd239da0d94cc4dd160ccf036d7)                                                                                                                                                                                                   |
| ~ 1 h  | Useful reading: Unsupervised Omics integration                                                                            | [Blog](https://medium.com/data-science/unsupervised-omics-integration-688bf8fa49bf?sk=191bb97826b8b0965708a6ec9b094529)                                                                                                                                                                                                   |
| ~ 1 h  | Useful reading: UMAP for data integration                                                                                 | [Blog](https://medium.com/data-science/umap-for-data-integration-50b5cfa4cdcd?sk=37149293008d917e6082552cc0edcd53)                                                                                                                                                                                                   |
| ~ 1 h  | Useful reading: Deep Learning for data integration                                                                        | [Blog](https://medium.com/data-science/deep-learning-for-data-integration-46d51601f781?sk=05dc5cd18d4c665acf8656c042d1cb45)                                                                                                                                                                                                   |



## Day 1: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                   | Link                                                                                                                                        |
|----------------|--------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 14.45  | Course outline and practical information: introductions                                    | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/course-outline-and-practical-info.pdf)         |
| 14.45 - 15.00  | Break                                                                                      |                                                                                                                                             |
| 15.00 - 16.00  | Introduction to biological Multi-Omics data integration via Machine Learning: key concepts | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/MachineLearningOmicsIntegration_Oskolkov.pdf)  |
| 16.00 - 16.15  | Break                                                                                      |                                                                                                                                             |
| 16.15 - 17.15  | Feature selection and supervised Omics integration                                         | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/SupervisedOmicsIntegration_Oskolkov.pdf)       |
| 17.15 - 17.30  | Break                                                                                      |                                                                                                                                             |
| 17.30 - 18.30  | Methods for univariate vs. multivariate feature selection: LASSO, PLS, LDA                 | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/OmicsIntegration_FeatureSelection.html)                                                                                                                                                                                                                     |
| 18.30 - 18.45  | Break                                                                                      |                                                                                                                                             |
| 18.45 - 20.00  | Methods for supervised Omics integration: mixOmics and DIABLO                              | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/supervised_omics_integr_CLL.html)                                                                                                                                                                                                                           |


## Day 2: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                    | Link                                                                                                                                       |
|----------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 15.00  | Unsupervised Omics integration: factor analysis and graph intersection                      | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/Unsupervised_OmicsIntegration_Oskolkov.pdf)   |
| 15.00 - 15.15  | Break                                                                                       |                                                                                                                                            |
| 15.15 - 16.45  | Methods for unsupervised Omics integration: MOFA1 and MOFA2                                 | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/UnsupervisedOMICsIntegration_MOFA2.html)                                                                                                                                                                                                                    |
| 16.45 - 17.00  | Break                                                                                       |                                                                                                                                            |
| 17.00 - 18.00  | Applications of artificial neural networks and Deep Learning to biological data integration | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/DeepLearningOmicsIntegration_Oskolkov.pdf)    |
| 18.00 - 18.15  | Break                                                                                       |                                                                                                                                            |
| 18.15 - 20.00  | Methods for Omics integration via neural networks: Autoencoder                              | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/DeepLearningDataIntegration.html)                                                                                                                                                                                                                           |


## Day 3: 2 pm - 8 pm Berlin time

| Time           | Activity                                                                                        | Link                                                                                                                                   |
|----------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| 14.00 - 15.00  | Dimensionality reduction and Omics integration with UMAP                                        | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/DimensionReduction_Oskolkov.pdf)          |
| 15.00 - 15.15  | Break                                                                                           |                                                                                                                                        |
| 15.15 - 15.45  | Methods for dimension reduction: comparison between PCA, tSNE, UMAP                             | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/OmicsIntegration_DimensionReduction.html)                                                                                                                                                                                                                   |
| 15.45 - 16.45  | Graph intersection method and UMAP application to Omics integration                             | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/UMAP_DataIntegration.html)                                                                                                                                                                                                                                  |
| 16.45 - 17.00  | Break                                                                                           |                                                                                                                                        |
| 17.00 - 18.00  | Batch correction (across samples) and Omics integration (across features) for single cell data  | [Slides](https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/raw/main/slides/Single_Cell_Integration_Oskolkov.pdf)     |
| 18.00 - 18.15  | Break                                                                                           |                                                                                                                                        |
| 18.15 - 19.30  | Methods for Omics integration for single cell data: Seurat CCA + DTW, WNN                       | [Lab](https://html-preview.github.io/?url=https://github.com/NikolayOskolkov/Physalia_MLOmicsIntegration_2025/blob/main/practicals/SingleCell_OmicsIntegration.html)                                                                                                                                                                                                                           |
| 19.30 - 20.00  | Questions and discussion                                                                        |                                                                                                                                        |


