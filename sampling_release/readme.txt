----------------------------------------------------------------
Package name: MPS_sampling, for uniform maximal Poisson-disk sampling on mesh surfaces

----------------------------------------------------------------
Usage example (the boundary file should be first in the ./data folder):
  gx_sampling.exe sphere.obj -rmin 0.03
  
Here rmin is the input Poisson-disk sampling radius, which will affect the number of points to be sampled.
please note the input mesh is first normalized to a unit bounding box before the sampling. Of course, we transform the results 
back to its original size.

Output: the sampled points in the format of .txt, as well as the remeshing result (in .obj), which are also located in ./data folder.

----------------------------------------------------------------
If you use this code, please cite the following paper:

@ARTICLE{Yan2013,
  author = {Dong-Ming Yan and Peter Wonka},
  title = {Gap Processing for Adaptive Maximal {P}oisson-Disk Sampling},
  journal = "ACM  Trans. on Graphics",
  year = {2013},
  volume = {32},
  number = {5},
  pages = {148:1-148:15},
}

or

@ARTICLE{Guo2014EMP,
  author = {Jianwei Guo and Dong-Ming Yan and Xiaohong Jia and Xiaopeng Zhang},
  title = {Efficient Maximal {P}oisson-disk Sampling and Remeshing on Surfaces},
  journal = {Computers \& Graphics},
  year = {2015},
  volume = {46},
  number = {6-8},
  pages = {72-79},
}

----------------------------------------------------------------
If you have any question, please don't hesitate to contact gjianwei.000@gmail.com