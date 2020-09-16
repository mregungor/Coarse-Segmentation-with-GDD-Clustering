# Coarse Segmentation
## Coarse Segmentation With GDD Clustering Using Color and Spatial Data
You can access the paper using the link below: <br>
https://ieeexplore.ieee.org/document/9163101

<p align="center">
<img  src="_img/Results/101087_fscmp_9_GDD_Result_43.png" alt="CoarseSeg_Color" width="200"/>
<img  src="_img/Results/101087_fsGndTrthcmp_2_GDDLabels_0.png" alt="CoarseSeg_Label" width="200"/>
<br>
<strong>Figure 1</strong> - Berkeley Segmentation Dataset 101087 image Coarse Segmentation Color (Left) & Label (Right) Output 
</p>


## Properties 
* +No parameter is needed
* +Intersection of two threads are used to obtain final segmentation result which currently segments images based on spatial and color data.
* +Resulting clusters do not change at different runs.
* -Segmentation outputs will  have outlier segments as it can be seen in Figure 1.
* -As clustering algorithm is not optimized for 2D images, run times are rather slow.


### <strong>[Please cite as]:</strong>
>  EGüngör, E., & Özmen, A. (2020). Coarse Segmentation With GDD Clustering Using Color and Spatial Data. IEEE Access, 8, 144880-144891. 


<br>
You can find test images from 
The Berkeley Segmentation Dataset and Benchmark:<br>
https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/

<br>
<br>
<strong>Useful links (compared methods included):</strong><br>
https://github.com/bonlime/keras-deeplab-v3-plus
<br>
https://github.com/divamgupta/image-segmentation-keras
