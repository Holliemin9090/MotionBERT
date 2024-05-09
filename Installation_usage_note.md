# Installation:
MotionBERT requires AlphaPose installation/build, which has been documented in (https://github.com/Holliemin9090/AlphaPose/blob/master/Custom_build.md).

But be aware that it needs to be installed in a lower python version (python3.8 I am using) under a conda/miniconda env.

Be careful with chumpy, which is one of the library it depends on. It may have a numpy cannot import bool issue, for numpy>=1.24. use pip install git+https://github.com/mattloper/chumpy
