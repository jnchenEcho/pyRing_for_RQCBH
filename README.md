# pyRing_for_RQCBH
Bayesian Inference for the rotating quantum corrected black hole (RQCBH) using `pyRing`. 

This model differs from the Kerr black hole by including an additional quantum correction term $\alpha M^2 / r^4$ in the $\Delta$ function.

We have introduced a new flag **RQC** in `pyRing` for the posterior inference of RQCBH, when **RQC**$= 1$ (default 0), the code uses QNM data derived from the RQCBH model with $s=0$ perturbation for parameter estimation. The QNM data with $s=-2$ perturbation is necessary in the future.

This repo corresponds to the paper: [arXiv:2510.27320v1](https://arxiv.org/abs/2510.27320). In that paper, we analyzed three gravitational-wave events — GW150914, GW190521, and GW231123. The configuration files used in the analysis are included in 
>pyring/pyRing/config_files/HPC_pyRing_RQC_accuracy/.

Since this is my first time conducting research by using this open-source code `pyRing` , please feel free to point out any issues, improper behaviour, or suggestions for improvement, contact: jnchenecho@foxmail.com.
