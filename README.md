# Paul-Scherrer-Institute-PSI

The notebook provides an algorithm able to reduce a certain class of two-loops tensor integrals in terms of a sum of one-loop squared integrals, general two-loop tadpoles and UV finite terms. For more information, see Extraction_of_UV_part_of_two_loop_tensor_integrals.pdf in this current repository.

The notebook is organized as follows:
- Packages
In this section all packages used in the notebook are loaded: X (https://packagex.hepforge.org/Documentation/HTML/X/guide/PackageX.html), HypExp (https://hypexp.hepforge.org/)
- UV degree
Here we define a procedure to extract the UV degree of divergence from the two-loops tensor integrals.
- Reduction algorithm
Here we design the algorithm able to achieve the task we are aiming at.
- Testing
In this section, we test the reduction algorithm on several integrals with different topologies.

The code has been also structured as a package. Nevertheless, the package is waiting for the complete results of the muon group at PSI to be released. In fact, this project of mine is part of a larger one, aiming to predict new physics beyond the Standard Model. Our code is used to extract the anomalous dimension of the operators involved. 
