# RPSL-Beyond-Uncertainty-AAAI
Multi-Objective Reinforcement Learning (MORL) arises in a wide range of real-world decision-making scenarios, where inherent uncertainty can lead to catastrophic consequences, such as traffic accidents or robotic failures. 
However, existing MORL methods struggle to maintain stable performance under various uncertainties, which may result in preference drift and convergence to a suboptimal Pareto Set.
To fill these gaps, we propose a novel MORL algorithm for Robust Pareto Set Learning (RPSL) via contrastive adversarial perturbations. RPSL enhances robustness against uncertainty from two distinct perspectives: 
(1) $\textit{Observation Perturbation}$ - we introduce multiple adversarial perturbation mechanisms to constrain the impact of observation perturbation within a bounded range, thereby improving the reliability of the learned policies.
(2) $\textit{Environmental Change}$ - we leverage contrastive learning to learn trajectories that are resilient to preference drift while preserving their discriminability, resulting in a more robust and diverse Pareto Set.
Experimental results show that RPSL outperforms state-of-the-art MORL methods by achieving a more convergent and more robust Pareto Set under uncertainty across five multi-objective benchmark environments.
