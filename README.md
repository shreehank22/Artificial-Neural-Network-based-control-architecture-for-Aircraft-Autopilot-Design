# ✈️ Artificial Neural Network-Based Control Architecture for Aircraft Autopilot Design

This repository presents a **robust autopilot design** for aircraft using **Artificial Neural Networks (ANNs)** as controllers. The research explores the potential of neural networks to replace traditional PID controllers in **nonlinear flight control systems**, allowing the system to adapt and maintain performance in varying flight conditions.

---

##  Key Highlights

*  Developed an **ANN-based controller** to replicate and eventually replace PID control behavior
*  Trained the ANN using data from a conventional **PID-controlled autopilot system**
*  Demonstrated the ANN’s ability to adapt to **nonlinear aircraft dynamics**
*  Validated performance through MATLAB/Simulink simulation
*  Offers a scalable, intelligent alternative to classic control techniques

---

##  Methodology Overview

1. **System Setup:**

   * Modeled an aircraft autopilot control system in Simulink.
   * Initially used a conventional **PID controller** for attitude and altitude control.

2. **ANN Training:**

   * Generated a dataset by logging input-output pairs from the PID-controlled system.
   * Trained a **feedforward ANN** to learn the control policy.

3. **Controller Substitution:**

   * Replaced the PID controller with the trained ANN in the closed-loop feedback structure.
   * Evaluated system stability, tracking accuracy, and adaptability to nonlinearities.

4. **Simulation and Validation:**

   * Verified ANN-based controller performance under various flight scenarios in Simulink.

---

##  Repository Structure

```
Artificial-Neural-Network-based-control-architecture-for-Aircraft-Autopilot-Design/
│
├── ANN_based_Controller.slx       # Simulink model with ANN controller
├── NN_FINAL_PAPER.slx             # Complete model used for final experiments
├── Paper.pdf                      # Research paper summarizing the methodology and results
├── README.md                      # Project documentation
```

---

##  Getting Started

### Requirements

* MATLAB R2020a or later
* Deep Learning Toolbox
* Simulink

### Steps to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shreehank22/Artificial-Neural-Network-based-control-architecture-for-Aircraft-Autopilot-Design.git
   cd Artificial-Neural-Network-based-control-architecture-for-Aircraft-Autopilot-Design
   ```

2. **Open MATLAB** and run the models:

   ```matlab
   open('NN_FINAL_PAPER.slx')     % For full simulation with ANN controller
   open('ANN_based_Controller.slx') % For modular ANN-based control model
   ```

3. **Run simulations** to compare PID and ANN-based performance.

---

##  Results Summary

* **ANN Controller** successfully mimics PID behavior after training.
* Exhibits **robust tracking** of desired flight paths even in nonlinear operating regimes.
* Demonstrates potential for **adaptive and intelligent flight control systems**.

---


##  Author

**Shreehan Kate**
For academic or industry collaboration, please feel free to reach out.

