# DeepSPT

2020 AnDi challenge 

Participated in AnDi challenge as a DeepSPT team.

------------ 
Taegeun Song(1),(2) Chang Beom Hong(1), and Jae-Hyung Jeon(1)

(1) Department of Physics, Pohang University of Science and Technology Pohang, Korea

(2) Center for AI and Natural Sciences, Korea Institute for Advanced Study, Korea

ResNet-MLP + XGBoost

We consider 7 classes: 
ATTM, CRTW, FBM (subdiffusive), Levy, SBM (subdiffusive), FBM (superdiffusive) and SBM (superdiffusive). 

20 features:
MSD exponent, diffusion constant, exponent of aging curve, amplitude of velocity, acceleration, scaling factor, Shapiro test, Anderson- darling test, from zero to forth momentum of position, velocity.

Two curves added in features: 
MSD, and aging curves, and each curve has a ten-points resolution.
