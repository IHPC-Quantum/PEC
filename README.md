# PEC

Probabilistic Error Cancellation (PEC) is one of the many error mitigation techniques. Instead of correcting hardware errors using error correction codes that demand many qubits, error mitigation aims to reduce the impact of hardware noise by taking advantage of classical computing. PEC consists of 4 main steps: 
1. Gate set tomography
2. Post-processing tomography data
3. Monte Carlo sampling
4. Post-processing the Monte Carlo outcomes

This repository houses two files. The first consists of functions for Gate set tomography, and the second is for the remaining parts of PEC. The functions for Gate set tomography are closely related to the pull request for Qibo's (https://github.com/qiboteam/qibo/pull/1106) and will be fixed as is at the time of upload regardless of further changes made to the pull request.

The files in this repository will be used to develop [the project] and the data collected over the course of [the project] will kept in the folder data for further analysis.
