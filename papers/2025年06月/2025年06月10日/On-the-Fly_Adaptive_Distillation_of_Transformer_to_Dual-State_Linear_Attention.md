# 实时自适应蒸馏：将 Transformer 转换为双状态线性注意力

发布时间：2025年06月10日

`LLM理论` `常识推理` `问答系统`

> On-the-Fly Adaptive Distillation of Transformer to Dual-State Linear Attention

# 摘要

> 大型语言模型（LLMs）擅长捕获全局令牌依赖，但处理长输入时计算和内存成本高昂。次二次方法（如线性注意力）虽能降低成本，却常因过度关注近期令牌而牺牲准确性。本研究提出了一种创新设计——	extbf{双状态线性注意力（DSLA）}，通过维护两个专用隐藏状态（一个保留历史上下文，一个跟踪近期信息）来缓解线性注意力架构的短程偏见。为在动态工作负载中平衡效率与准确性，我们开发了	extbf{SERVE}框架，它通过在线自适应蒸馏，在推理时逐步用DSLA层替换Transformer层，基于敏感度排序确保层间一致性。实验表明，SERVE在常识推理、长上下文问答和文本摘要任务中，推理速度比Llama2-7B快2.3倍，比混合Zamba-7B快3.0倍，同时保持性能。消融研究证实，DSLA的双状态有效解决了传统线性注意力的历史令牌代表性不足问题。代码已开源：https://github.com/utnslab/DSLA-Serve。

> Large language models (LLMs) excel at capturing global token dependencies via self-attention but face prohibitive compute and memory costs on lengthy inputs. While sub-quadratic methods (e.g., linear attention) can reduce these costs, they often degrade accuracy due to overemphasizing recent tokens. In this work, we first propose \textit{dual-state linear attention} (\textbf{\dsla}), a novel design that maintains two specialized hidden states-one for preserving historical context and one for tracking recency-thereby mitigating the short-range bias typical of linear-attention architectures. To further balance efficiency and accuracy under dynamic workload conditions, we introduce \textbf{\serve}, an online \textit{adaptive distillation} framework that progressively replaces Transformer layers with DSLA layers at inference time, guided by a sensitivity-based layer ordering. \serve\ uses a chained fine-tuning strategy to ensure that each newly converted DSLA layer remains consistent with previously replaced layers, preserving the overall quality. Extensive evaluations on commonsense reasoning, long-context QA, and text summarization demonstrate that \serve\ yields \textbf{2.3x} faster inference than Llama2-7B and \textbf{3.0x} faster than the hybrid Zamba-7B, while retaining comparable performance across downstream tasks. Our ablation studies show that DSLA's dual states capture both global and local dependencies, addressing the historical-token underrepresentation seen in prior linear attentions. Codes are available at https://github.com/utnslab/DSLA-Serve.

[Arxiv](https://arxiv.org/abs/2506.09316)