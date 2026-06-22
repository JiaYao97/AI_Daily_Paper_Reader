## 最新日报
- 最新运行日期：2026-06-22
- 运行时间：2026-06-22 22:49:04 UTC
- 运行状态：成功
- 本次总论文数：22
- 精读区：9
- 速读区：13

### 今日简报（AI）
今日精读22篇论文，重点攻克流体力学界面破碎与浅水方程摩擦估计两大难题。最值得关注的是《Learning Interface Breakup》提出的几何条件潜代理模型（9.0分）和《How Sparse and How Noisy》对物理信息神经网络的系统基准测试（9.0分）。建议首先精读这两篇9分论文，理解其方法论创新，再结合速读中的GPU代理模型（8.0分）探索加速实际物理仿真的路径。
- 详情：[/202606/22/README](/202606/22/README)

### 精读区论文标签
1. [Learning Interface Breakup: A Geometry-Conditioned Latent Surrogate for Spray Formation](/202606/22/2606.16587v1-learning-interface-breakup-a-geometry-conditioned-latent-surrogate-for-spray-formation)  
   标签：评分：9.0/10、query:flow-field
   evidence：几何条件潜在代理用于喷雾形成; 降阶建模
2. [How Sparse and How Noisy? Systematic Benchmarking of Inverse Physics-Informed Neural Networks for Manning Friction Estimation in Shallow Water Equations](/202606/22/2606.18149v1-how-sparse-and-how-noisy-systematic-benchmarking-of-inverse-physics-informed-neural-networks-for-manning-friction-estimation-in-shallow-water-equations)  
   标签：评分：9.0/10、query:flow-field
   evidence：物理信息神经网络用于浅水方程逆建模
3. [A Convex Quasilinearization Method for Solving Nonlinear PDEs with Physics-Informed Neural Networks](/202606/22/2606.18175v1-a-convex-quasilinearization-method-for-solving-nonlinear-pdes-with-physics-informed-neural-networks)  
   标签：评分：9.0/10、query:flow-field
   evidence：用于求解非线性PDE的物理信息神经网络
4. [LGNO: A Local-Global Neural Operator for Hyperbolic Conservation Laws](/202606/22/2606.18221v1-lgno-a-local-global-neural-operator-for-hyperbolic-conservation-laws)  
   标签：评分：9.0/10、query:flow-field
   evidence：用于双曲守恒律的局部-全局神经算子
5. [Solution of the Newtonian plane Couette flow with dynamic wall slip using machine-learning methods](/202606/22/2606.18499v1-solution-of-the-newtonian-plane-couette-flow-with-dynamic-wall-slip-using-machine-learning-methods)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用物理信息神经网络和深度算子网络预测平面库埃特流
6. [Acceleration of an algebraic multigrid pressure solver using graph neural networks](/202606/22/2606.19251v1-acceleration-of-an-algebraic-multigrid-pressure-solver-using-graph-neural-networks)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用图神经网络加速流场模拟中的压力求解
7. [Advances in Scientific Machine Learning for Coupled Fluid Flow and Transport](/202606/22/2606.19562v1-advances-in-scientific-machine-learning-for-coupled-fluid-flow-and-transport)  
   标签：评分：9.0/10、query:flow-field
   evidence：流体流动预测与重建的科学机器学习综述
8. [Phonon-mediated stabilization of first and second modes in hypersonic boundary-layer flows](/202606/22/2606.19673v1-phonon-mediated-stabilization-of-first-and-second-modes-in-hypersonic-boundary-layer-flows)  
   标签：评分：9.0/10、query:q1
   evidence：通过减阻和热载荷减轻实现高超声速热防护
9. [State estimation of Rayleigh-Bénard convection with reduced-order models](/202606/22/2606.20511v1-state-estimation-of-rayleigh-bnard-convection-with-reduced-order-models)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用降阶模型对瑞利-贝纳德对流进行状态估计

### 速读区论文标签
1. [Accelerating Kinetic Fokker-Planck Simulations via a GPU-Native Deep Neural Network Surrogate: Application to Rarefied Internal and Hypersonic External Flows](/202606/22/2606.15622v1-accelerating-kinetic-fokker-planck-simulations-via-a-gpu-native-deep-neural-network-surrogate-application-to-rarefied-internal-and-hypersonic-external-flows)  
   标签：评分：8.0/10、query:q1
   evidence：用于高超声速外流动力学模拟的神经代理模型
2. [Phys-JEPA: Physics-Informed Latent World Models for Multivariate Time-Series Forecasting](/202606/22/2606.16076v1-phys-jepa-physics-informed-latent-world-models-for-multivariate-time-series-forecasting)  
   标签：评分：8.0/10、query:pclso
   evidence：物理信息潜在世界模型，用于多变量预测并施加物理约束
3. [Random-Feature Kalman Filtering for Linear PDE Data Assimilation](/202606/22/2606.16086v1-random-feature-kalman-filtering-for-linear-pde-data-assimilation)  
   标签：评分：8.0/10、query:flow-field
   evidence：随机特征卡尔曼滤波用于线性PDE数据同化
4. [PhysGuard: Fisher-Guided Gradient Projection for Sim-to-Real Neural PDE Surrogates](/202606/22/2606.16602v1-physguard-fisher-guided-gradient-projection-for-sim-to-real-neural-pde-surrogates)  
   标签：评分：8.0/10、query:flow-field
   evidence：神经算子仿真到真实PDE代理的适应
5. [A Validated LBM Dataset and Pipeline for Surrogate Modeling of Turbulent 3D Obstructed Channel Flows](/202606/22/2606.16765v1-a-validated-lbm-dataset-and-pipeline-for-surrogate-modeling-of-turbulent-3d-obstructed-channel-flows)  
   标签：评分：8.0/10、query:flow-field
   evidence：验证的LBM数据集用于湍流替代建模，基于神经算子
6. [Liquid Random Feature Methods for Time-Dependent Partial Differential Equations](/202606/22/2606.15571v1-liquid-random-feature-methods-for-time-dependent-partial-differential-equations)  
   标签：评分：7.0/10、query:flow-field
   evidence：用于时间相关PDE（包括流体流动）的液体随机特征方法
7. [A GPGPU-Oriented Full Phase-Space Parallel Unified Gas-Kinetic Scheme with Velocity-Block Pipelining](/202606/22/2606.15720v1-a-gpgpu-oriented-full-phase-space-parallel-unified-gas-kinetic-scheme-with-velocity-block-pipelining)  
   标签：评分：7.0/10、query:flow-field
   evidence：面向GPGPU的UGKS气体动力学流场模拟
8. [Engine position effects on contrail evolution for a realistic aircraft configuration](/202606/22/2606.16390v1-engine-position-effects-on-contrail-evolution-for-a-realistic-aircraft-configuration)  
   标签：评分：7.0/10、query:flow-field
   evidence：使用LES和RANS模拟飞机尾迹和轨迹演化
9. [Petrov-Galerkin Variational Physics-Informed Neural Network Framework for Two-Dimensional Singularly Perturbed Problems](/202606/22/2606.16510v1-petrov-galerkin-variational-physics-informed-neural-network-framework-for-two-dimensional-singularly-perturbed-problems)  
   标签：评分：7.0/10、query:flow-field
   evidence：变分物理信息神经网络，用于具有尖锐边界层的问题，可应用于流体动力学
10. [Pixels to Proofs: Probabilistically-Safe Latent World Model Control via Parallel Conformal Robust MPC](/202606/22/2606.15594v1-pixels-to-proofs-probabilistically-safe-latent-world-model-control-via-parallel-conformal-robust-mpc)  
   标签：评分：6.0/10、query:pclso
   evidence：潜在动力学与约束学习
11. [Quantum-enhanced Markov chain Monte Carlo sampling to model Lagrangian tracer dispersion in turbulent boundary layer](/202606/22/2606.15985v1-quantum-enhanced-markov-chain-monte-carlo-sampling-to-model-lagrangian-tracer-dispersion-in-turbulent-boundary-layer)  
   标签：评分：6.0/10、query:flow-field
   evidence：使用计算MCMC方法模拟湍流边界层中的拉格朗日示踪粒子弥散
12. [Closing the Approximation Gap in Simulation-free Latent SDEs](/202606/22/2606.16138v1-closing-the-approximation-gap-in-simulation-free-latent-sdes)  
   标签：评分：6.0/10、query:pclso
   evidence：潜变量SDE用于动力系统
13. [Optimizing Multiple Feature Types for Image Inpainting in the Linear and Nonlinear Setting](/202606/22/2606.16581v1-optimizing-multiple-feature-types-for-image-inpainting-in-the-linear-and-nonlinear-setting)  
   标签：评分：6.0/10、query:flow-field
   evidence：图像修复中特征优化，类比流场重构

