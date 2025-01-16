# Quantum Real-time Evolution using Tensor Renormalization Group Methods
This repository includes HOTRG time evolution operators and projectors for ArXiv paper arXiv:2411.05301. They are stored in individual numpy arrays. The naming scheme is as follows:

- hotrg-TM-Ns[number of sites]-lam[nearest-neighbor coupling]-dt[time step]-dcut[cutoff].npy
- hotrg-Umats-Ns[number of sites]-lam[nearest-neighbor coupling]-dt[time step]-dcut[cutoff].png

The TM file contains a single $(d_{cut}, d_{cut})$ time evolution operator for the given parameters, and the Umats file contains $n = \log_2N_s$ projectors that is used to build operators. The paper briefly mentions how they are used. My PhD thesis will be published at a later date, and will contain clear instructions on how to use them.
