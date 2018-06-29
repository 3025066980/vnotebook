# The Application of Machine Learning for the Adaptive mmWave-NOMA Systems
## Abstract
- Non-orthogonal multiple access (NOMA) has emerged as a promising radio access technique for enabling the performance enhancements promised by the fifth-generation (5G) networks in terms of massive connectivity, lower latency, and higher spectrum efficiency.

- This paper investigates the coexistence between NOMA and millimeterwave (mmWave) communications, a key enabling technologies for 5G too.

- We demonstrate by simulations that the proposed method ....

## Introduction
- Non-orthogonal multiple access (NOMA) has received considerable attention in both industry and academia for addressing the dramatically increasing demand for massive user access, heterogeneous data traffic, high bandwidth efficiency, and ultra-low latency services. The key concept of NOMA is to accommodate multiple users in the same orthogonal resource block, such as time slots, frequency bands, and spatial directions. By doing so, high bandwidth efficiency and massive connectivity can be attained. Because of its superior performance, NOMA has already been included in the 3rd generation partnership project long-term evolution advanced (3GPP-LTE-A) standard, the next general digital TV standard (ATSC 3.0), and the 5G New Radio (NR) standard.

- Millimeter-wave (mmWave) communications around and above 30 GHz can achieve multigigabit data rates for indoor communications. However, compared with current cellular systems, mmWave communications have much higher carrier frequencies. It is well known that the higher the carrier frequency is, the higher the propagation path loss is experienced in wireless communications [13]. Fortunately, the decrease in the wavelength of mmWave makes it possible to place a very large number of antennas in a much smaller region. Large antenna arrays are able to provide highly directional beamforming gains via precoding, which helps overcome the propagation path loss and increase the link reliability. Moreover, larger antenna arrays can transmit multiple streams via spatial multiplexing, which helps improve spectral efficiency. However, with the increase in the number of antennas at the transmitter, the number of radio frequency (RF) chains required by fully digital beamforming (DBF) is equal to the number of antennas, which is unrealistic in terms of cost, complexity, thermal overshoot, and implementation within a small form factor at the UE side.

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
- A. Benjebbour, K. Saito, A. Li, Y. Kishiyama, and T. Nakamura, “Nonorthogonal multiple access (noma): Concept, performance evaluation and experimental trials,” in 2015 International Conference on Wireless Networks and Mobile Communications (WINCOM), Oct 2015, pp. 1–6.
- [12] M. N. Kulkarni, A. Ghosh, and J. G. Andrews, “A comparison of MIMO techniques in downlink millimeter wave cellular networks with hybrid beamforming,” IEEE Trans. Commun., vol. 64, no. 5, pp. 1952–1967, May 2016.
- [13] G. Lee, Y. Sung, and J. Seo, “Randomly-directional beamforming in millimeter-wave multiuser MISO downlink,” IEEE Trans. Wireless Commun., vol. 15, no. 2, pp. 1086–1100, Feb. 2016.
- 