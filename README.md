# Crop Rotation

Crop rotation is the agricultural practice of growing a series of different crops in a set of areas, called plots, over time. Crop rotation has benefits that include improved soil structure and reduced dependence on pesticides, herbicides, and fertilizers.

The approach used here involves the use of a Constrained Quadratic Model (CQM) from Dwave (https://github.com/dwave-examples/crop-rotation). The solution is computed using the LeapHybridCQMSampler. The challenge is coped on D-wave using a DQM. In this notebook instead the problem was solved using a CQM. The results obtained with this model show a much better performance (in terms of a greater soil utilization), if compared with the DQM used by the authors.



## References
Santos, L. M. R. dos et al. "Crop rotation scheduling with adjacency constraints." Springer Science+Business Media, LLC, 26 Nov. 2008.
