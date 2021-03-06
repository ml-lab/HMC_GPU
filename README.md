HMC_GPU
=======

This code can be used to replicate the results found in:

[Beam, Andrew L., Sujit K. Ghosh, and Jon Doyle. "Fast hamiltonian monte carlo using gpu computing." Journal of Computational and Graphical Statistics.](http://www.tandfonline.com/doi/abs/10.1080/10618600.2015.1035724#.V0zZ2lfEyJU)

The preprint can be accessed here:
http://arxiv.org/abs/1402.4089

To get started you will need to make sure you have the following depedencies installed:

GPU Computing Environment:
- Cuda SDK 5.0: https://developer.nvidia.com/cuda-toolkit
- CULA (needed by the python scikit below): http://www.culatools.com/

Python Environment
- Python 2.7: http://www.python.org/
- Numpy - http://www.numpy.org/
- SciPy - http://www.scipy.org/
- PyCuda - http://mathema.tician.de/software/pycuda/
- CUDA SciKit: http://scikits.appspot.com/cuda

Additionally, if you would like to run the glmnet comparison, you will need to install the following:
- R: http://cran.us.r-project.org/
- glmnet: http://cran.r-project.org/web/packages/glmnet/index.html
- doMC (for parallel processing in R - Linux): http://cran.r-project.org/web/packages/doMC/index.html
- doSNOW (for parallel processing in R - Windows): http://cran.r-project.org/web/packages/doSNOW/index.html

Each script is a self-contained file that corresponds to one set of results in the manuscript. The first time you run the
code you may recieve some text indicating compiler warnings. This is expected and can be safely ignored.

The MNIST data used in the maunscript can be found here:

http://yann.lecun.com/exdb/mnist/
