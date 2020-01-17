In the file "largesth31.txt", we present the 1d rays and 3d cones of the base B_{max} that supports the elliptic CY4 with largest h31=303148. It is used in the paper 1511.03209.

In the file "otherlargeh31.txt", we also present a number of smooth toric threefold bases that support elliptic CY4s with large h31.

The format of the bases is:

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

In the file "otherlargeh31.txt", we also write a line below each base containing the estimated h11 and h31 of the elliptic CY4 over it, in the format:
h11 "h31="h31