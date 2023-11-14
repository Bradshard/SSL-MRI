# SSL-MRI
Self-Supervised Representation Learning for phantom MRI Images

Finished for now. since PD is already in the interval of [0-1] and e^(-/a,b,c) will make something in the range of [0-1] already ranges [0-1] so, even with no normalization, it is in that range.
In R3 we require 3x3 9 equations to make the learning from the physics possible mathematically, however; we do not have 9 MRI image function. One can with known PD's or for any two of three parameters can find the
solution from SSL from such loss function applied to find MR maps.
