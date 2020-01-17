After decompressing the three tar.gz files together, the file "bases.txt" includes the toric end point threefold bases found in the paper arXiv:1710.11235, with Hodge number 1000<h11<13000

The format of the files is:

# of 1d rays in the toric fan
v_{i,x} v_{i,y} v_{i,z} (list of the 3 coordinates of the 1d rays)
# of 3d cones in the toric fan
i_1 i_2 i_3 (each 3d cone has three rays with labels i_1 i_2 i_3)

Next base...

For example, the base P3 would be
4
1 0 0
0 1 0
0 0 1
-1 -1 -1
4
0 1 2
0 1 3
0 2 3
1 2 3

Note that the label of rays starts from 0.

