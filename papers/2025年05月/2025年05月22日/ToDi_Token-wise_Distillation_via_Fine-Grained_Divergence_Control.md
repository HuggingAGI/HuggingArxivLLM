# ToDi：逐 Token 蒸馏，通过精细散度控制

发布时间：2025年05月22日

`LLM理论` `模型压缩` `模型优化`

> ToDi: Token-wise Distillation via Fine-Grained Divergence Control

# 摘要

> 大型语言模型（LLMs）虽然性能出众，但因高延迟和能耗，在资源受限的部署中并不适用。知识蒸馏（KD）通过将大型模型的知识迁移到更小的模型来解决这一问题。然而，传统蒸馏方法如前向KL散度（FKL）和反向KL散度（RKL）在词汇表上采用统一的散度损失，忽视了词级别的预测差异。通过梯度分析，我们发现FKL增强被低估的词，而RKL抑制被高估的词，二者互补。基于此，我们提出了Token-wise Distillation（ToDi），通过基于教师-学生概率对数比率的sigmoid加权函数，为每个词自适应结合FKL和RKL。ToDi能动态强调每个词的合适散度，实现精确的分布对齐。在多个指令遵循基准测试中，ToDi始终优于现有基线。消融研究和效率分析进一步证明了ToDi的有效性和实用性。

> Large language models (LLMs) offer impressive performance but are impractical for resource-constrained deployment due to high latency and energy consumption. Knowledge distillation (KD) addresses this by transferring knowledge from a large teacher to a smaller student model. However, conventional KD, notably approaches like Forward KL (FKL) and Reverse KL (RKL), apply uniform divergence loss across the entire vocabulary, neglecting token-level prediction discrepancies. By investigating these representative divergences via gradient analysis, we reveal that FKL boosts underestimated tokens, while RKL suppresses overestimated ones, showing their complementary roles. Based on this observation, we propose Token-wise Distillation (ToDi), a novel method that adaptively combines FKL and RKL per token using a sigmoid-based weighting function derived from the teacher-student probability log-ratio. ToDi dynamically emphasizes the appropriate divergence for each token, enabling precise distribution alignment. We demonstrate that ToDi consistently outperforms recent distillation baselines using uniform or less granular strategies across instruction-following benchmarks. Extensive ablation studies and efficiency analysis further validate ToDi's effectiveness and practicality.

[Arxiv](https://arxiv.org/abs/2505.16297)