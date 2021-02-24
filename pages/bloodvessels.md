
## [Home](/index) / [Brief CV](/brief_cv) / Research / [News](/news)

___

## Francisco J. López-Tiro 
**Email:** [`francisco.lopez@inaoe.mx`](mailto:francisco.lopez@inaoe.com?subject=%20Hello,%20Francisco)

[[Twitter]](https://twitter.com/Friscolt)
[[GitHub]](https://github.com/friscolt)
[[Linkedin]](https://www.linkedin.com/in/friscolt)
[[Academic]](https://scholar.google.es/citations?user=IlG06bYAAAAJ&hl=es)

---

## Visualization and localization of blood vessels in speckle images


Our research helps to improve the visualization of blood vessels inside the biological tissue. To achieve this goal we carry out research in biophotonics, high noise signals, digital image processing, and segmentation algorithms. 

We assume that if we can attenuate the noise in the region of the blood vessel, the contrast will increase, and consequently visualization will improve. There are two main drawbacks to this: attenuating the noise and locating the region of interest. 

In this research we address the use of the Discrete Wavelet Transform (DWT) as a multilevel filtering method and region segmentation techniques to improve visualization and localization in LSI images. 


| Work | Dataset |    Methods   | Localization | Visualization | Performance |
|:----:|:-------:|:------------:|:------------:|:-------------:|:-----------:|
|`[1]` | `Set A` | `DWT-SL+MM`  |       ✔️     |       ✔️      | `JI: 0.8`  |
|`[2]` | `Set B` | `DWT-SL+KNN` |       ✔️     |               | `JI: 0.9`  |
|`[3]` | `Set A` | `DWT-AL+MM`  |       ✔️     |       ✔️      | `JI: 0.1`  |


### Work:

1. [*Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition*](https://ieeexplore.ieee.org/document/8827144)
2. [*Effect of the Exposure Time in Laser Speckle Imaging for Improving Blood Vessels Localization: a Wavelet Approach*](https://ieeexplore.ieee.org/document/9129242/)
3. Visualization of Blood Vessels in in-vitro Raw Speckle Images Using an Energy-based Decomposition Criteria on DWT Coefficients

### Datasets:

*  `Set A:` *in-vitro* straight and bifurcated blood vessels at 0µm to 900µm
*  `Set B:` *in-vitro* straight blood vessels at 0µm to 1000µm

### Methods: 

* `DWT-SL + MM:` Discrete Wavelet Transform of simple level with mathematical morphology 
* `DWT-SL + KNN:` Discrete Wavelet Transform of simple level with KNN classifier
* `DWT-AL + MM:` Discrete Wavelet Transform automatic level with mathematical morphology 


### Performance:

* JI: Jaccard Index




