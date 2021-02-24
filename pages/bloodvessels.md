
## [Home](/index) / [Brief CV](/brief_cv) / [Research](/research) / [News](/news)
___

## Visualization and localization of blood vessels in speckle images









|     Work     |     Dataset     |         Methods         | Localization | Visualization | Performance |
|:------------:|:---------------:|:-----------------------:|:------------:|:-------------:|:-----------:|
|   [1]        |  *In-vitro I*   |       DWT-SL + MM       |       ✔️      |       ✔️     |   JI: 0.8   |
|   [2]        |  *In-vitro II*  | DWT-SL + KNN            |       ✔️      |              |   JI: 0.9   |
|   [3]        |  *In-vitro I*   |       DWT-AL + MM       |       ✔️      |       ✔️     |   JI: 0.10  |
___


Work:

* [1] [**Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition**](https://ieeexplore.ieee.org/document/8827144)
* [2] [**Effect of the Exposure Time in Laser Speckle Imaging for Improving Blood Vessels Localization: a Wavelet Approach**](https://ieeexplore.ieee.org/document/9129242/)
* [3] Visualization of Blood Vessels in in-vitro Raw Speckle Images Using an Energy-based Decomposition Criteria on DWT Coefficients

Datasets:

*  *In-vitro I:* Straight (0um to 1000um)
*  *In-vitro II:* Straight and bifurcated (0um to 900um)

Methods: 

* DWT-SL + MM : Discrete Wavelet Transform of simple level with mathematical morphology 
* DWT-SL + KNN: Discrete Wavelet Transform of simple level with KNN classifier
* DWT-AL + MM: Discrete Wavelet Transform automatic level with mathematical morphology 


Metric:

* JI: Jaccard Index




