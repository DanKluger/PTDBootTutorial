This repository has an RMarkdown file titled "Tutorial" giving examples that demonstrate how to use the PTDBoot package. It also includes a folder with the processed datasets that were used in the examples. Finally there is also a RMarkdown file with code that applied some functions from the PTDBoot package to a partially synthetic, corn yield dataset.

## Dataset citations

If using the processed datasets, please cite their original source rather than this github repository.

The housing price and treecover datasets came from: 
> Rolf, E., Proctor, J., Carleton, T., Bolliger, I., Shankar, V., Ishihara, M., Recht, B., and
Hsiang, S. (2021a). A generalizable and accessible approach to machine learning with
global satellite imagery. Nature Communications, 12(1):4392.
> Rolf, E., Proctor, J., Carleton, T., Bolliger, I., Shankar, V., Ishihara, M., Recht, B., and
Hsiang, S. (2021b). A generalizable and accessible approach to machine learning with
global satellite imagery. https://www.codeocean.com/capsule/6456296/tree/v2.


The AlphaFold dataset had origins and was later processed in:
> Bludau, I., Willems, S., Zeng, W.-F., Strauss, M. T., Hansen, F. M., Tanzer, M. C., Karayel,
O., Schulman, B. A., and Mann, M. (2022). The structural context of posttranslational
modifications at a proteome-wide scale. PLoS biology, 20(5):e3001636.
> Angelopoulos, A. N., Bates, S., Fannjiang, C., Jordan, M. I., and Zrnic, T. (2023b).
Prediction-powered inference: Data sets. 10.5281/zenodo.8397451.

The Census income dataset was from an official US survey, but was downloaded using the Folktables interface:
> Ding, F., Hardt, M., Miller, J., and Schmidt, L. (2021). Retiring adult: New datasets for
fair machine learning. In Advances in Neural Information Processing Systems.

Note that for each of these datasets, [additional processing steps](https://github.com/DanKluger/Predict-Then-Debias_Bootstrap/blob/main/Datasets/ReadAndProcessData.Rmd) were taken before uploading the data to this repository. 

## Software citations

The software and PTDBoot package should be attributed to:

> Dan M. Kluger, Kerri Lu, Tijana Zrnic, Sherrie Wang, and Stephen Bates (2025). Prediction-Powered Inference with Imputed Covariates and Nonuniform Sampling. 2501.18577 [stat.ME]  [https://arxiv.org/abs/2501.18577](https://arxiv.org/abs/2501.18577)
