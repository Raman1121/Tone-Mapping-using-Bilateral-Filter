# Tone-Mapping-using-Bilateral-Filter
This repository contains the implementation of Tone Mapping technique using edge-aware Bilateral Filter. 

This is an implementation of the paper "Fast Bilateral Filtering for the Display of High-Dynamic-Range Images" by Fr´edo Durand and Julie Dorsey.

PiecewiseBilateral
(Image I, spatial kernel fss , intensity influence gsr )
J=0 /* set the output to zero */
for j=0..NB SEGMENTS
i j= minI+j  (max(I)-min(I))/NB SEGMENTS
Gj=gsr (I - ij ) /* evaluate gsr at each pixel */
K j=Gj

 fss /* normalization factor */
H j=Gj
 I /* compute H for each pixel */
H j=H j

 fss
J j=H j /K j /* normalize */
J=J+J j
 InterpolationWeight(I, ij )