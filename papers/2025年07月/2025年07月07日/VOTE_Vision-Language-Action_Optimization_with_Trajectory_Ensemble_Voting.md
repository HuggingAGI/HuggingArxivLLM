# VOTE：基于轨迹集成投票的视觉-语言-动作优化

发布时间：2025年07月07日

`LLM应用` `机器人` `计算机视觉`

> VOTE: Vision-Language-Action Optimization with Trajectory Ensemble Voting

# 摘要

> 近期，大规模视觉语言动作（VLA）模型在自然语言指导下的机器人操作任务中表现卓越。然而，这些模型在处理新物体或陌生环境时的泛化能力仍有待提升。现有方法通常通过引入深度估计、分割或扩散等附加组件来增强泛化，但此举显著增加了计算负担，导致效率低下。为解决这一问题，我们探索了一种高效的动作预测方法，无需依赖额外的高级视觉表征或扩散技术。本研究提出了名为VOTE的高效通用框架，用于优化和加速VLA模型。具体而言，我们创新性地提出了一种无需分词器的微调方法，可实现并行精准动作预测，从而显著减少计算开销并加快推理速度。此外，我们采用集成投票策略进行动作采样，这不仅显著提升了模型性能，还增强了其泛化能力。实验结果表明，我们的方法实现了最先进性能，推理速度提升了35倍，吞吐量达到145Hz。所有细节和代码将开放共享。

> Recent large-scale Vision Language Action (VLA) models have shown superior performance in robotic manipulation tasks guided by natural language. However, their generalization remains limited when applied to novel objects or unfamiliar environments that lie outside the training distribution. To address this, many existing approaches integrate additional components such as depth estimation, segmentation, or even diffusion to improve generalization, at the cost of adding significant computation overhead, resulting in low efficiency. This motivates the exploration of efficient action prediction methods, which are independent of additional high-level visual representations or diffusion techniques. In this work, we propose VOTE, an efficient and general framework for the optimization and acceleration of VLA models. In details, we propose a novel tokenizer-free fine-tuning approach for parallel accurate action prediction, which reduces computational overhead and accelerates inference speed. Additionally, we adopt an ensemble voting strategy for the action sampling, which significantly improves model performance and enhances generalization. Experimental results show that our method achieves state-of-the-art performance with 35$\times$ faster inference and 145 Hz throughput. All the details and codes will be open-sourced.

[Arxiv](https://arxiv.org/abs/2507.05116)