# Optuna 与 Code Llama 对比：LLMs 是否开启超参数调优新篇章？

发布时间：2025年04月08日

`LLM应用` `边缘计算` `机器学习`

> Optuna vs Code Llama: Are LLMs a New Paradigm for Hyperparameter Tuning?

# 摘要

> 超参数的最优选择对于提升神经网络性能至关重要，尤其是当模型复杂度增加时。本研究探索了使用大型语言模型（LLMs）进行超参数优化的可能性，采用了微调后的Code Llama版本。通过利用LoRA进行参数高效的微调，我们将LLM调整为能够生成精准且高效的超参数建议，这些建议针对多种神经网络架构进行了定制。与依赖全面试验的传统方法如Optuna不同，我们的方法在均方根误差（RMSE）方面达到了具有竞争力甚至更优的结果，同时显著降低了计算开销。我们的研究表明，基于LLM的优化不仅能够匹敌树形Parzen估计器等先进方法，还能加速调优过程。这使LLMs成为传统优化技术的有前途替代方案，尤其适合快速实验场景。此外，该方法能在单次推理中生成超参数，使其特别适用于计算效率至关重要的资源受限环境，如边缘设备和移动应用。结果表明，LLMs不仅高效，还带来了显著的时间节省和相当的稳定性，突显了其在推进机器学习工作流程中的价值。所有生成的超参数已整合至公开的LEMON神经网络（NN）数据集，该数据集作为超参数优化研究的开源基准。

> Optimal hyperparameter selection is critical for maximizing neural network performance, especially as models grow in complexity. This work investigates the viability of using large language models (LLMs) for hyperparameter optimization by employing a fine-tuned version of Code Llama. Through parameter-efficient fine-tuning using LoRA, we adapt the LLM to generate accurate and efficient hyperparameter recommendations tailored to diverse neural network architectures. Unlike traditional methods such as Optuna, which rely on exhaustive trials, the proposed approach achieves competitive or superior results in terms of Root Mean Square Error (RMSE) while significantly reducing computational overhead. Our approach highlights that LLM-based optimization not only matches state-of-the-art methods like Tree-structured Parzen Estimators but also accelerates the tuning process. This positions LLMs as a promising alternative to conventional optimization techniques, particularly for rapid experimentation. Furthermore, the ability to generate hyperparameters in a single inference step makes this method particularly well-suited for resource-constrained environments such as edge devices and mobile applications, where computational efficiency is paramount. The results confirm that LLMs, beyond their efficiency, offer substantial time savings and comparable stability, underscoring their value in advancing machine learning workflows. All generated hyperparameters are included in the LEMUR Neural Network (NN) Dataset, which is publicly available and serves as an open-source benchmark for hyperparameter optimization research.

[Arxiv](https://arxiv.org/abs/2504.06006)