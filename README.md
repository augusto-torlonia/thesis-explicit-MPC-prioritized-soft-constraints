# Master Thesis | Explicit MPC with Prioritized Soft Constraints

This repository contains my Mater's Thesis document, in which I discuss the simulation results obtained by implementing in Matlab a novel version of explict Model Predictive Controller which allows to relax soft constraints according to their assigned level of priority.

## 📌 Project Overview
* **Objective:** Enhance existing Explicit MPC methodologies by introducing the capability to dynamically select and relax soft constraints based on assigned priority levels, ensuring continuous control action and preventing system failure under critical or infeasible states.
* **Methodology:** Built upon previous exact penalty methods (1-norm regularization) to compute a limit piece-wise affine map. The core innovation lies in scaling multiple penalty coefficients to infinity in a strict, sequential order according to their priority, allowing the controller to systematically sacrifice lower-priority constraints first.
* **Tools Used:** MATLAB, MPT3 Toolbox.

## 📊 Key Engineering & Theoretical Contributions
1. **Infeasibility Management:** Developed a robust relaxation strategy for explicit optimal control laws using 1-norm penalties to avoid undefined controller states.
2. **Multi-Level Prioritization:** Formulated and implemented the tuning logic for multi-tier penalty coefficients, ensuring that lower-priority soft constraints are relaxed before higher-priority ones.


## 📁 Repository Structure
* 📄 `[Master's-Thesis-Augusto-Torlonia].pdf` - Full Master's Thesis document including theoretical foundations, algorithm formulation, and simulation results.

---
*Note: Due to university licensing and intellectual property management, the MATLAB scripts are not publicly shared in this repository. However, all theoretical frameworks, algorithms, and validation plots are fully documented within the PDF document.*

