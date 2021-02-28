
## [Home](/index) / [Brief CV](/brief_cv) / [Research](/research) / [News](/news) / [Contact](/contact)

---

## Visualization and localization of blood vessels in speckle images



![Visualization and localization of blood vessels in speckle images](/images/bloodvessels.png)




Our research helps to improve the visualization of blood vessels inside the biological tissue. To achieve this goal we carry out research in biophotonics, high noise signals, digital image processing, and segmentation algorithms. 




We assume that if we can attenuate the noise in the region of the blood vessel, the contrast will increase, and consequently visualization will improve. There are two main drawbacks to this: attenuating the noise and locating the region of interest. 

In this research we address the use of the Discrete Wavelet Transform (DWT) as a multilevel filtering method and region segmentation techniques to improve visualization and localization in LSI images. 


| Work | Dataset |    Methods   | Localization | Visualization | Performance |
|:----:|:-------:|:------------:|:------------:|:-------------:|:-----------:|
|`[1]` | `Set A` | `DWT-SL+MM`  |       ✔️     |       ✔️      | `JI: 0.XX`  |
|`[2]` | `Set B` | `DWT-SL+KNN` |       ✔️     |               | `JI: 0.XX`  |
|`[3]` | `Set A` | `DWT-AL+MM`  |       ✔️     |       ✔️      | `JI: 0.XX`  |


### Work

1. *Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition* [[Paper]](https://ieeexplore.ieee.org/document/8827144) [[Code]](https://github.com/friscolt/i2mtc-2019)

2. *Effect of the Exposure Time in Laser Speckle Imaging for Improving Blood Vessels Localization: a Wavelet Approach* [[Paper]](https://ieeexplore.ieee.org/document/9129242/) [[Code]](https://github.com/friscolt/i2mtc-2020) 

3. Visualization of Blood Vessels in in-vitro Raw Speckle Images Using an Energy-based Decomposition Criteria on DWT Coefficients

### Datasets

*  `Set A:` 
   *  *in-vitro* straight (7) and bifurcated (7) blood vessels at 0µm to 900µm 
   *  The following dataset contains 14 packets of raw speckle images
   
*  `Set B:` 
   * *in-vitro* straight blood vessels at 0µm to 1000µm 
   * The following dataset contains 90 packets of raw speckle images


### Methods

* `DWT-SL + MM:` Discrete Wavelet Transform of simple level with mathematical morphology 
* `DWT-SL + KNN:` Discrete Wavelet Transform of simple level with KNN classifier
* `DWT-AL + MM:` Discrete Wavelet Transform automatic level with mathematical morphology 

### Performance

* JI: Jaccard Index