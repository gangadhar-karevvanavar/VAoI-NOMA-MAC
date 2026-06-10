# Version AoI Optimization under Power and General Distortion Constraints in Uplink NOMA

This repository contains simulation codes for the paper:

**"Version AoI Optimization under Power and General Distortion Constraints in Uplink NOMA"**

---

## Paper Summary

This work studies Version Age of Information (VAoI) minimization in an uplink non-orthogonal multiple access (NOMA) wireless system under average power and information-quality constraints.

VAoI measures information freshness as the number of versions by which the receiver lags behind the transmitter. In the considered system, multiple users maintain single-packet buffers and transmit updates to a common receiver over fading wireless channels.

A key trade-off arises between:
- Information freshness
- Transmission power
- Information quality

Transmitting more bits improves reconstruction quality but requires higher power, reducing transmission opportunities and increasing VAoI. Conversely, transmitting fewer bits reduces power consumption but increases distortion.

The work formulates a weighted-sum VAoI minimization problem under:
- Average transmit power constraints
- General distortion constraints
- Multiple-access channel capacity constraints

The proposed framework investigates:
- Joint scheduling and power allocation
- Bit allocation optimization
- Successive interference cancellation (SIC) decoding order optimization
- Uplink NOMA transmission strategies
- Comparison with TDMA systems

Key contributions include:
- Convex optimization formulation for weighted VAoI minimization
- Development of a VAoI-agnostic stationary randomized policy
- Provable 2-approximation guarantee to the globally optimal VAoI
- Lagrangian dual decomposition based solution framework
- Closed-form scheduling probabilities and power allocation expressions
- Efficient SIC decoding order determination without exhaustive search
- General distortion modeling supporting unequal bit importance

Simulation results demonstrate:
- Significant VAoI gains of NOMA over TDMA
- Near-zero VAoI achievable with NOMA at high power budgets
- TDMA saturation at non-zero VAoI values
- Strong dependence between distortion constraints and achievable freshness

The proposed general distortion framework can model diverse information-priority structures by assigning different importance levels to transmitted bits.

---

## Paper Links

### arXiv
[arXiv Preprint](https://arxiv.org/abs/2603.28631)

