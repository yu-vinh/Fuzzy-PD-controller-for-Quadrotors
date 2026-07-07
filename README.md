# Fuzzy-PD-controller-for-Quadrotors (Matlab r2025a)

In this case, I simulated a fuzzy filter with a 2-input 1-output structure and used two parallel branches for the fuzzy inference system (FIS) of delta Kp and delta Kd.

Regarding the simulation environment, with dx=dy=dz=d_phi=d_theta=d_psi = 0 (error), the results were very good with a very small difference between the desired trajectory and the calculated trajectory (approximately 0.01%).
I simulated this project based on https://doi.org/10.1016/j.rico.2025.100568
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/33d6bda1-49a5-427b-9d9e-c7be9719fba1" />
