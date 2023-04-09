# Classification-and-enumeration-of-lattice-polygons-in-a-disc
This is the resulting dataset of the paper 

Liu Q, Zhang Y, Cai Z. Classification and enumeration of lattice polygons in a disc[J]. arXiv preprint arXiv:2303.14899, 2023.

The files "list_of_polygons_radius_2", "list_of_polygons_radius_3" and "list_of_polygons_radius_4" contain the lists of non-equivalent convex lattice polygons in the disc of radius 2, 3 and 4 respectively. Each of them contains several files in .txt format. The txt file named by "lattice_point_i" contains the list of lattice polygons with i lattice points. In every txt file, the matrix named by "r(i)_lp(j)_(k)" denotes the k-th representative element with j lattice points in the disc of raidus i. For example, the matrix named by "r3_lp4_2" denotes the second representative element with 4 lattice points in the disc of raidus 3.

The files "list_of_polygons_radius_2.mat", "list_of_polygons_radius_3.mat" and "list_of_polygons_radius_4.mat" contain the lists of non-equivalent convex lattice polygons in the disc of radius 2, 3 and 4 respectively, which can be read by MATLAB directly. Each of these three files contains two columns of cells, the i-th cell in the first column contains the non-equivalent lattice polygons with i+2 lattice points, and the i-th cell in the second column contains only a number, i+2.

Every lattice polygon is represented by a matrix in this dataset, of which each row is the coordinates of a vertex of the lattice polygon.
