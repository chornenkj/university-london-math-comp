# university-london-math-comp

This repository contains materials and scripts I have created while learning 'Mathematics for Computer Sciences' course of University of London.

The repository consists:
1. Script on Python in Jupiter Notebook for staganography task. The task was to decode hidden colours, and read hidden message in images. Each image given contains 16 colour values 4x4. As we work with colours, there is functions to convert RGB into hex format and vise verse. R, G and B values of each colour contain hidden values in 4 right bits. So, the script slices those 4 right bits, moves them to the left to create new R, G and B values for each colour out of 16 of each image. And finally script prints received images using 'ipycanvas' module.

!This repository is not for other learners, but instead it is to present my skills I have obtained on this course
