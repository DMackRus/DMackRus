## Hi, I'm Dave👋

I am a PhD student at the University of Leeds working on **robotic manipulation!**

The general work of my PhD has been focused on methods of using approximation / simplifications to speed up trajectory optimisation, especially for manipulation in clutter. The two main pieces of work of my PhD so far have been on the following:

- [TrajOptKP - Efficient Contact-based Trajectory Optimisation via Apprxoimated Derivatives](https://github.com/DMackRus/TrajOptKP) - Speeding up gradient-based trajectory optimisation by only computing dynamics derivatives at **key-points**, and interpolating the rest!
- [Autonomous State Vector Reduction During Online MPC for High-dimensionality Trajectory Optimisation](https://github.com/DMackRus/TrajOptKP/blob/main/src/Optimiser/iLQR_SVR.cpp) - Dynamically changing the size of the state vector during live MPC for manipulation of high DoF systems. (currently under review)

Both of these works are focused on speeding up trajectory optimisation times whilst trying to minimse any degradation in performance. This is especially useful in MPC where it is usually more important to optimise a trajectory as fast as possible, and not get too hung up on optimality.

To finish my PhD I am interested in combining learning methods with trajectory optimisation, again in the same vein as my previous two works.

📫 If you want to reach out about anything here is my email! el16dmcr@leeds.ac.uk
