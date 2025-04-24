# Chronos模型助力有效波高预测提升

发布时间：2025年04月23日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于波浪预测这一具体任务中，展示了其在时序数据建模中的应用。Chronos作为专为波浪预测优化的LLM驱动架构，展示了在计算效率、预测准确性和零样本能力方面的突破，属于LLM的实际应用案例。` `海洋学` `时序建模`

> Improving Significant Wave Height Prediction Using Chronos Models

# 摘要

> 精确的波高预测是保障海上安全和海岸韧性的关键，但传统物理模型和机器学习方法在计算效率和非线性动力学建模方面仍存在局限。本研究推出Chronos——首个专为波浪预测优化的大型语言模型（LLM）驱动的时序架构。基于西北太平洋 basin 三个关键海域的历史波浪数据，Chronos通过先进的时序模式识别技术，实现了四大突破：（1）相比PatchTST基线，训练时间缩减14.3%，推理速度提升2.5倍，达到0.575的平均绝对标度误差（MASE）；（2）在短期预测（1-24小时）中表现卓越；（3）在中长期预测（1-120小时）中持续领先；（4）展现出强大的零样本预测能力，在与专业运营模型的对比中保持中位数性能（排名第4/12）。Chronos这一LLM增强的时序建模范式不仅为波浪预测树立了新标杆，更为复杂地球物理系统建模提供了高效且可迁移的解决方案。

> Accurate wave height prediction is critical for maritime safety and coastal resilience, yet conventional physics-based models and traditional machine learning methods face challenges in computational efficiency and nonlinear dynamics modeling. This study introduces Chronos, the first implementation of a large language model (LLM)-powered temporal architecture (Chronos) optimized for wave forecasting. Through advanced temporal pattern recognition applied to historical wave data from three strategically chosen marine zones in the Northwest Pacific basin, our framework achieves multimodal improvements: (1) 14.3% reduction in training time with 2.5x faster inference speed compared to PatchTST baselines, achieving 0.575 mean absolute scaled error (MASE) units; (2) superior short-term forecasting (1-24h) across comprehensive metrics; (3) sustained predictive leadership in extended-range forecasts (1-120h); and (4) demonstrated zero-shot capability maintaining median performance (rank 4/12) against specialized operational models. This LLM-enhanced temporal modeling paradigm establishes a new standard in wave prediction, offering both computationally efficient solutions and a transferable framework for complex geophysical systems modeling.

[Arxiv](https://arxiv.org/abs/2504.16834)