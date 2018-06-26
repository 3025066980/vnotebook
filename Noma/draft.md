# The Application of Machine Learning for the Adaptive mmWave-NOMA Systems
## Abstract
- This paper investigates the coexistence between two key enabling technologies for fifth generation (5G) mobile networks, non-orthogonal multiple access (NOMA) and millimeterwave (mmWave) communications.
## Introduction
- Non-orthogonal multiple access (NOMA) has received considerable attention in both industry and academia for addressing the dramatically increasing demand for massive user access, heterogeneous data traffic, high bandwidth efficiency, and ultra-low latency services. The key concept of NOMA is to accommodate multiple users in the same orthogonal resource block, such as time slots, frequency bands, and spatial directions. By doing so, high bandwidth efficiency and massive connectivity can be attained. Because of its superior performance, NOMA has already been included in the 3rd generation partnership project long-term evolution advanced (3GPP-LTE-A) standard, the next general digital TV standard (ATSC 3.0), and the 5G New Radio (NR) standard.

- The multi-user nature of the NOMA principle implies that a NOMA network is a typical example of complex systems, to which recent advances in machine learning and big data signal processing promise significant advantages in terms of the performance-complexity tradeoff.
## System Model
- Consider a mmWave-NOMA downlink transmission scenario with one base station communicating with multiple users. The base station is equipped with $N_t$ antennas and each user has $N_r$ antenna.

- As discussed in [12] and [13], the mmWave channel model is quite different from those of conventional lower frequency cellular networks; in particular, the mmWave-based channel vector from the base station to user k can be expressed as follows:
$$h_k = \sqrt{N_t}\frac{}{} + \sqrt{N_t}\sum_{l=1}^L\frac{}{}$$
where $L$ is denoted as the number of i.i.d paths:
$$a(\theta) = \frac{1}{N_t}[1, e^{-j\pi\theta}, ... , e^{-j\pi(M-1)theta}]^T$$

## Problem Formulation

## Simulation Results

## Conclusions

## References
- [12] M. N. Kulkarni, A. Ghosh, and J. G. Andrews, “A comparison of MIMO techniques in downlink millimeter wave cellular networks with hybrid beamforming,” IEEE Trans. Commun., vol. 64, no. 5, pp. 1952–1967, May 2016.
- [13] G. Lee, Y. Sung, and J. Seo, “Randomly-directional beamforming in millimeter-wave multiuser MISO downlink,” IEEE Trans. Wireless Commun., vol. 15, no. 2, pp. 1086–1100, Feb. 2016.