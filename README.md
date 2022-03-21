# interlopers_with_lenstronomy

This is a collection of jupyter notebooks that demonstrate the analysis of the
gravitational lensing system JVAS B1938+666. You can find the corresponding
paper at https://arxiv.org/abs/2112.00749.

Curl-and-div.ipynb
shows the important aspects of the lens model such as
the curl and the convergence differences for the case of an interloper
at various redshifts from that of a subhalo.

Mock_Images.ipynb
shows how we create a mock image with a given set of parameters which
we later recover with our modeling.

Subhalo_Mass_Function.ipynb
shows how we make the calculations that show the effect of mistakenly
counting interlopers as subhalos as well as probing dark matter using
interlopers.

Visualize_Data.ipynb
shows how the nested sampling results are loaded. Makes the figures in the paper.

PDFs_of_models.ipynb
shows the full PDFs of the models mentioned in Table 1 of the paper.

jvas_nested2.py
the code that runs the nested sampling analysis on the image
using various lens model types.



dynesty version=1.1

lenstronomy version=1.9.1
