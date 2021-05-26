# BigBrain Surface Parcellations

## BigBrain

The BigBrain is the brain of a 65 years old man with no neurological or psychiatric
diseases in clinical records at time of death. The brain was embedded in parafin and
sectioned in 7404 coronal histological sections (20 microns), stained for cell bodies.
The BigBrain is the digitized reconstruction of the hi-res histological sections 
(20 microns isotropic).

## Dataset content

This dataset contains surface parcellations from the BigBrain release 2015 
published in the [BigBrain Project website](https://bigbrainproject.org).

Commonly used surface atlases previously defined on fsaverage (Brainnetome, DKT, Economo, Schaefer2018) and HCP's fs_LR (MMP 1.0) have been mapped onto the BigBrain. Surface-based registration has been achieved using a customized MSM pipeline. 

The data is organized as follows:

- fsaverage folder: contains atlases on fsaverage projected on the resampled BigBrain surfaces in fsaverage space
- fs_LR folder: contains atlases on fs_LR projected on the resampled BigBrain surgaces in fs_LR space.
- BigBrain_space folder: contains resampled labels of the various atlases defined on the original BigBrain surfaces.

## Reference and more information

If you are using this dataset, please cite:

Lewis, L.B., Lepage, C.Y., Glasser, M.F., Coalson, T.S., Van Essen, D.C., 
and Evans, A.C. (2019). 'An extended MSM surface registration pipeline to 
bridge atlases across the MNI and the FS/HCP worlds', OHBM poster, Rome.

Lewis, L.B., Lepage, C.Y., Glasser, M.F., Coalson, T.S., Van Essen, D.C.,
and Evans, A.C. (2020, submitted). 'An improved MSM surface registration 
pipeline to bridge atlases across the MNI and the FS/HCP worlds', OHBM poster, 
Montreal / virtual.

The references for the atlases are:

1) Brainnetome:

Fan, L. et al. (2016). 'The Human Brainnetome Atlas: a new brain atlas 
based on connectional architecture', Cerebral Cortex 26:3508-26.


2) DKT:

Desikan, R.S. et al. (2006). 'An automated labeling system for subdividing 
the human cerebral cortex on MRI scans into gyral based regions of interest', 
NeuroImage 31(3):968-80.

Klein, A., and Tourville, J. (2012). '101 labeled brain images and a consistent 
human cortical labeling protocol', Frontiers in Neuroscience 6(171).


3) Economo:

Scholtens, L.H. et al. (2018). 'An MRI Von Economo - Koskinas atlas', NeuroImage, 
170:249-256.


4) Schaefer2018:

Schaefer, A. et al. (2018). 'Local-global parcellation of the human cerebral 
cortex from intrinsic functional connectivity MRI', Cerebral Cortex 29:3095-3114.

5) HCP:

Glasser, M.F. et al. (2016). 'A multi-modal parcellation of human cerebral 
cortex', Nature 536:171-178.

6) BigBrain reference:

The BigBrain dataset is the result of a collaborative effort between the
teams of Dr. Katrin Amunts and Dr. Karl Zilles (Forschungszentrum Jülich)
and Dr. Alan Evans (Montreal Neurological Institute). 

Amunts, K. et al.: "BigBrain: An Ultrahigh-Resolution 3D Human
Brain Model", Science (2013) 340 no. 6139 1472-1475, June 2013.
[https://www.sciencemag.org/content/340/6139/1472.abstract](https://www.sciencemag.org/content/340/6139/1472.abstract)


For more information please visit the [BigBrain Project website](https://bigbrainproject.org).
