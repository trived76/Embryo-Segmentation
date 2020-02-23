# Centroid calculation of the blastomere from 3D Z-Stack image data of a 2-cell mouse embryo

The repository is currently update. Essentially, the repository contains the information about the following research paper.
DOI: https://doi.org/10.1016/j.bspc.2019.101726

## Highlights

1. 3D Z-stack Mouse embryo image data was captured by a bright field inverted microscope.
2. Existing image processing operations were used to segment cell area in each 2D image.
3. 3D centroid coordinates were calculated from segmented z-stack images.
4. Cell volume was reconstructed in 3D for visualization of the calculated 3D centroid.
5. Cell manipulation tasks can be automated with 3D centroid and image-based feedback.

## Abstract
During cell surgery, cell manipulation tasks such as placement of cells, extraction of organelles, blastomeres, or other structures from within a cell are essential. To enable these tasks, it is necessary to locate the centroid of such objects within a cell, to be able to position micromanipulators to carry out such tasks. Calculation of the centroid of objects within a cell is necessary to enable vision-based feedback control to micromanipulators for automation of cell tasks. In this paper, we propose a methodology to address the calculation of the centroid of blastomeres within a mouse embryo. This is achieved with z-stack image data from 2D cell images. Z-stack images are captured at uniform intervals over the cell depth, by keeping the embryo fixed and moving the focal plane. Individual (2D) images of the z-stack are then processed. Blastomeres in each image are segmented with existing image processing techniques and converted to mask images. From these masked images, the 2D blastomere image centroids are calculated, allowing the centroid of the blastomere volume in 3D to be computed. The proposed calculation of the blastomere centroid is a critical step in determining the centroid of objects within a cell, to facilitate automation of cell surgery tasks.

If you find the work useful, please do not forget to cite it:
```
@article{trivedi2020centroid,
  title={Centroid calculation of the blastomere from 3D Z-Stack image data of a 2-cell mouse embryo},
  author={Trivedi, Maharshi M and Mills, James K},
  journal={Biomedical Signal Processing and Control},
  volume={57},
  pages={101726},
  year={2020},
  publisher={Elsevier}
}
```
