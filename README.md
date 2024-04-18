# Image_compression_modified_Lz77
I have done this from a research paper a new coding method for lossless gray-scale image compression. Our method is based on rnodifications of LZ77-based compression and estimation of prediction errors of pixels. 
Our met hod gives compression comparable to JPEG loss- less mode and its speed is about twice that of JPEG lossless mode with arithmetic coding.

Compression Algorithm 
To describe our compression method, we use the 
following notations. 
I: value of a pixel to be encoded. i: prediction of I. 
E: prediction error of I (E = I - I). 
E. estimation of E. 
 B: number of bits to express E. B: estimation of B. 
Zi,J-l, Z2-1,3, I$-I,~-~: 
values of immediate left pixel. 
immediate above pixel. and immediate left above pixel 
of the pixel to be encoded
