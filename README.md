# RPC_cheetah

Policy Regularized Model Predictive Control simulated by matlab 

参考论文

Policy Regularized Model Predictive Control Framework for Robust Legged Locomotion

使用casadi实现了其中的非线性优化部分，使用cheetah softwared的框架，由非线性优化替换了凸优化部分，实现了一个简单的仿真，但是效果很差。

The nonlinear optimization part was implemented using casadi, and the convex optimization part was replaced by nonlinear optimization using the framework of cheetah softwared, and a simple simulation was achieved, but the effect was very poor.

![Quadruped Trajectory Optimization](NLP_2022-05-22-19-33_trot.gif)
