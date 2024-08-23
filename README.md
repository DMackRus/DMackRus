## Hi, I'm Dave👋

I am a PhD student at the University of Leeds working on **robotic manipulation!**

The general work of my PhD has been focused on methods of using approximations / simplifications to speed up trajectory optimisation, especially for manipulation in clutter. The two main pieces of work of my PhD so far have been on the following:

- Speeding up gradient-based trajectory optimisation via approximating dynamics derivatives over a trajectory. We only compute dynamics derivatives at certain timesteps (keypoints) over the trajectory and then interpolate the rest! This work was presented at [ICRA2023](https://eprints.whiterose.ac.uk/197059/1/ICRA23_0389_FI.pdf), and the project source code is [here](https://github.com/DMackRus/Dynamic_Interpolation_iLQR). This work is currently being extended to a journal paper, my new [repository](https://github.com/DMackRus/TrajOptKP) takes this first ideas significantly further on a wide variety of tasks!
- Speeding up gradient-based trajectory optimisation via operating on a reduced state vector. This reduced state vector changes **dynamically** during online MPC! This work was presented at [WAFR2024](https://arxiv.org/abs/2408.11665v1), and the project source code is [here](https://github.com/DMackRus/iLQR-SVR).

Both of these works are focused on speeding up trajectory optimisation times whilst trying to minimse any degradation in performance. This is especially useful in MPC where it is usually more important to optimise a trajectory as fast as possible, and not get too hung up on optimality.

To finish my PhD I am interested in combining learning methods with trajectory optimisation, again in the same vein as my previous two works.

📫 If you want to reach out about anything here is my email! el16dmcr@leeds.ac.uk
