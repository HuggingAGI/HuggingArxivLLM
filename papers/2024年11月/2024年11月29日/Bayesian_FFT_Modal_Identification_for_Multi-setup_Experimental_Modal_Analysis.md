# 用于多设置实验模态分析的贝叶斯 FFT 模态识别

发布时间：2024年11月29日

`其他` `振动测试` `结构工程`

> Bayesian FFT Modal Identification for Multi-setup Experimental Modal Analysis

# 摘要

> 在全尺寸强迫振动测试中，常常面临在传感器和激振器数量有限的情况下获取高空间分辨率振型的需求。多装置实验模态分析（EMA）通过在多个装置间移动传感器和激振器来应对这一难题。为实现快速且精确的多装置EMA，本文拓展现有单装置算法，开发出一种贝叶斯模态识别策略。具体来说，先利用多组结构多输入多输出（MIMO）振动数据构建频域概率模型，再运用约束拉普拉斯方法进行贝叶斯后验近似，给出模态参数的最大后验估计以及用于不确定性量化的后验协方差矩阵（PCM）。借助复杂矩阵微积分，推导出坐标下降优化中的参数更新以及PCM计算的解析表达式，既简化了编码，又提升了计算效率。通过对合成数据和现场数据的实例研究，对所提算法进行了深度验证。结果显示，与测试设备充足的情况相比，所提方法得出的结果高度一致。所得的高保真MIMO模型能够预测未来加载条件下的结构响应，并为状态评估提供支持。

> In full-scale forced vibration tests, the demand often arises to capture high-spatial-resolution mode shapes with limited number of sensors and shakers. Multi-setup experimental modal analysis (EMA) addresses this challenge by roving sensors and shakers across multiple setups. To enable fast and accurate multi-setup EMA, this paper develops a Bayesian modal identification strategy by extending an existing single-setup algorithm. Specifically, a frequency-domain probabilistic model is first formulated using multiple sets of structural multiple-input, multiple-output (MIMO) vibration data. A constrained Laplace method is then employed for Bayesian posterior approximation, providing the maximum a posteriori estimates of modal parameters along with a posterior covariance matrix (PCM) for uncertainty quantification. Utilizing complex matrix calculus, analytical expressions are derived for parameter updates in the coordinate descent optimization, as well as for PCM computation, enhancing both coding simplicity and computational efficiency. The proposed algorithm is intensively validated by investigating empirical examples with synthetic and field data. It demonstrates that the proposed method yields highly consistent results compared to scenarios with adequate test equipment. The resulting high-fidelity MIMO model enables structural response prediction under future loading conditions and supports condition assessment.

[Arxiv](https://arxiv.org/abs/2412.00318)