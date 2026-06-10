## 最新日报
- 最新运行日期：2026-06-10
- 运行时间：2026-06-10 23:00:58 UTC
- 运行状态：成功
- 本次总论文数：24
- 精读区：11
- 速读区：13

### 今日简报（AI）
今日精读重点聚焦降阶模型与神经算子谱偏差校正，同时速读覆盖波流相互作用、等变3D PDE求解器及模型误设校正。

最值得关注的两大方向：旋转环流局部强迫降阶模型（9.0分）和利用稀疏观测的扩散后验采样校正神经算子谱偏差（9.0分）。

建议优先阅读这两篇精读文章，以掌握物理约束与数据驱动结合的前沿思路，然后扩展至波流相互作用等应用场景。
- 详情：[/202606/10/README](/202606/10/README)

### 精读区论文标签
1. [Reduced Order Model for a Convective Rotating Annulus with Localized Forcing](/202606/10/2606.03275v2-reduced-order-model-for-a-convective-rotating-annulus-with-localized-forcing)  
   标签：评分：9.0/10、query:flow-field
   evidence：旋转流体环形区域的降阶Galerkin模型
2. [Correcting Neural Operator Spectral Bias via Diffusion Posterior Sampling with Sparse Observations](/202606/10/2606.03936v1-correcting-neural-operator-spectral-bias-via-diffusion-posterior-sampling-with-sparse-observations)  
   标签：评分：9.0/10、query:flow-field
   evidence：用扩散后验采样纠正神经算子谱偏差
3. [A Reduced-Order Particle-in-Cell Method with Azimuthal Fourier-Decomposed Fields for Nominally Axisymmetric Plasmas](/202606/10/2606.04887v2-a-reduced-order-particle-in-cell-method-with-azimuthal-fourier-decomposed-fields-for-nominally-axisymmetric-plasmas)  
   标签：评分：9.0/10、query:flow-field
   evidence：降阶建模
4. [Mamba-Assisted Non-Markovian Closure for Reduced-Order Modeling](/202606/10/2606.05371v1-mamba-assisted-non-markovian-closure-for-reduced-order-modeling)  
   标签：评分：9.0/10、query:flow-field
   evidence：基于Mamba的闭合模型用于高维系统的降阶建模
5. [Wall Shear Stress Reconstruction from Concentration: Differentiable Physics and Physics-Informed Neural Networks](/202606/10/2606.06313v1-wall-shear-stress-reconstruction-from-concentration-differentiable-physics-and-physics-informed-neural-networks)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用可微物理和物理信息神经网络从浓度观测重建流体壁面剪切应力
6. [Unified Geometry-Guided ML-FTLE for Tracking Transient Chaos from Scalar Time Series](/202606/10/2606.07385v1-unified-geometry-guided-ml-ftle-for-tracking-transient-chaos-from-scalar-time-series)  
   标签：评分：9.0/10、query:pclso
   evidence：ML-FTLE提取潜在几何成分用于流体流动混沌跟踪
7. [Operator learning for the 2D incompressible Navier-Stokes equations: a conformal prediction approach in the data-scarce regime](/202606/10/2606.08654v1-operator-learning-for-the-2d-incompressible-navier-stokes-equations-a-conformal-prediction-approach-in-the-data-scarce-regime)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用FNO对纳维-斯托克斯方程进行算子学习
8. [A Hybrid Generative Reduced-Order Model for the Minimal Flow Unit](/202606/10/2606.09044v1-a-hybrid-generative-reduced-order-model-for-the-minimal-flow-unit)  
   标签：评分：9.0/10、query:pclso
   evidence：用于湍流的自编码器降阶模型，结合稀疏传感器
9. [Boundary-Layer-Induced Failure of Standard Physics-Informed Neural Networks: A Legendre Wavelet Collocation Benchmark for Singularly Perturbed Transport Problems](/202606/10/2606.09676v1-boundary-layer-induced-failure-of-standard-physics-informed-neural-networks-a-legendre-wavelet-collocation-benchmark-for-singularly-perturbed-transport-problems)  
   标签：评分：9.0/10、query:flow-field
   evidence：标准PINN在边界层奇异摄动传输问题上的失败基准
10. [Geometry-Aware Anisotropic Boundary Correction for Aerodynamic Simulation](/202606/10/2606.09963v1-geometry-aware-anisotropic-boundary-correction-for-aerodynamic-simulation)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用神经算子的几何条件各向异性边界修正用于气动模拟
11. [Data-driven surrogate models for forecasting experimentally measured fluid flows](/202606/10/2606.10848v1-data-driven-surrogate-models-for-forecasting-experimentally-measured-fluid-flows)  
   标签：评分：9.0/10、query:flow-field
   evidence：使用神经网络和傅里叶神经算子的数据驱动代理模型预测实验测量的流体流动

### 速读区论文标签
1. [A reduced model for surface wave-current interactions without spatial scale separation](/202606/10/2606.03231v1-a-reduced-model-for-surface-wave-current-interactions-without-spatial-scale-separation)  
   标签：评分：8.0/10、query:flow-field
   evidence：波浪-流相互作用的简化渐近模型
2. [EqGINO: Equivariant Geometry-Informed Fourier Neural Operators for 3D PDEs](/202606/10/2606.03260v1-eqgino-equivariant-geometry-informed-fourier-neural-operators-for-3d-pdes)  
   标签：评分：8.0/10、query:flow-field
   evidence：等变傅里叶神经算子用于3D PDE，可直接应用于流体动力学
3. [Physics-guided correction for operator learning under model misspecification](/202606/10/2606.03469v1-physics-guided-correction-for-operator-learning-under-model-misspecification)  
   标签：评分：8.0/10、query:flow-field
   evidence：算子学习求解PDE
4. [Uncovering Turbulent Dynamics in Stenotic Flows from 4D-flow MRI Measurements via Resolvent Analysis and Data Assimilation](/202606/10/2606.03838v1-uncovering-turbulent-dynamics-in-stenotic-flows-from-4d-flow-mri-measurements-via-resolvent-analysis-and-data-assimilation)  
   标签：评分：8.0/10、query:flow-field
   evidence：物理信息神经网络用于流体流动数据同化
5. [Loss-Conditional PINNs for Parametric PDE Families](/202606/10/2606.04420v1-loss-conditional-pinns-for-parametric-pde-families)  
   标签：评分：8.0/10、query:flow-field
   evidence：参数PDE的物理信息神经网络
6. [Input-to-State Stable Bundle Koopman Neural ODEs for Learning Controlled Dynamics under Environmental Constraints](/202606/10/2606.04395v1-input-to-state-stable-bundle-koopman-neural-odes-for-learning-controlled-dynamics-under-environmental-constraints)  
   标签：评分：7.0/10、query:flow-field
   evidence：用于学习受控动力学的Koopman神经ODE
7. [Curvature-aware dynamic precision approach for physics-informed neural networks](/202606/10/2606.04736v1-curvature-aware-dynamic-precision-approach-for-physics-informed-neural-networks)  
   标签：评分：7.0/10、query:flow-field
   evidence：通过精度自适应改进PINNs用于流体流动
8. [Generalized Forcing Method: Generation of Diverse Data for Training Linear Transport PDE Closure Models](/202606/10/2606.05141v1-generalized-forcing-method-generation-of-diverse-data-for-training-linear-transport-pde-closure-models)  
   标签：评分：7.0/10、query:flow-field
   evidence：用于训练传输PDE闭合模型的数据生成框架
9. [Learning solution operators of PDEs with sparse approximation methods](/202606/10/2606.06046v1-learning-solution-operators-of-pdes-with-sparse-approximation-methods)  
   标签：评分：7.0/10、query:flow-field
   evidence：适用于流场的PDE解算子的稀疏逼近方法
10. [A Systematic Benchmark of Physics-Informed Neural Network Architectures for the Stiff Poisson-Nernst-Planck System: Adaptive LossWeighting and Multi-Scale Resolution](/202606/10/2606.04125v1-a-systematic-benchmark-of-physics-informed-neural-network-architectures-for-the-stiff-poisson-nernst-planck-system-adaptive-lossweighting-and-multi-scale-resolution)  
   标签：评分：6.0/10、query:flow-field
   evidence：PINN架构在刚性PDE上的基准测试，可迁移到流体PINN应用
11. [An Energy-Stable Implicit Convex-Splitting BDF2 Scheme for the Cahn-Hilliard-Navier-Stokes Equations](/202606/10/2606.04204v1-an-energy-stable-implicit-convex-splitting-bdf2-scheme-for-the-cahn-hilliard-navier-stokes-equations)  
   标签：评分：6.0/10、query:flow-field
   evidence：Navier-Stokes方程的能量稳定格式，实现精确流场模拟
12. [An algebraic multiscale preconditioner for large sparse SPD matrices](/202606/10/2606.04864v1-an-algebraic-multiscale-preconditioner-for-large-sparse-spd-matrices)  
   标签：评分：6.0/10、query:flow-field
   evidence：用于达西流模拟的代数多尺度预处理器
13. [DiffSlack: Learning under Nonlinear Inequality Constraints via Learnable Slack Variables](/202606/10/2606.05247v1-diffslack-learning-under-nonlinear-inequality-constraints-via-learnable-slack-variables)  
   标签：评分：6.0/10、query:pclso
   evidence：通过可学习松弛变量进行约束学习

