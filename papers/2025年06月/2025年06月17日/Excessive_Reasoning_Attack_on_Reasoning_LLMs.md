# 过度推理攻击对推理型大语言模型的影响

发布时间：2025年06月17日

`LLM理论` `大型语言模型` `推理优化`

> Excessive Reasoning Attack on Reasoning LLMs

# 摘要

> 近期，OpenAI o1 和 DeepSeek-R1 等推理型大型语言模型（LLMs）通过推理规模扩展在复杂任务上表现出强大的性能。然而，这些模型常常因过度推理而产生显著的计算成本，例如频繁切换推理轨迹（如思考不足）或在简单问题上进行冗余推理（如过度思考）。在此研究中，我们揭示了一种新型威胁：对抗输入可以被设计出来，利用过度推理行为，在不降低模型实用性的情况下，显著增加计算开销。因此，我们提出了一种由三个组件组成的新型损失框架：（1）优先交叉熵损失，这是对标准交叉熵目标的修改，通过利用语言模型的自回归特性来强调关键标记；（2）过度推理损失，它鼓励模型在推理过程中启动额外的推理路径；（3）延迟终止损失，旨在延长推理过程并推迟最终输出的生成。我们在 DeepSeek-R1-Distill-LLaMA 和 DeepSeek-R1-Distill-Qwen 上优化并评估了我们的攻击方法，针对 GSM8K 和 ORCA 数据集。实证结果表明，推理长度增加了 3 倍到 9 倍，同时保持了相当的实用性性能。此外，我们设计的对抗输入具有迁移性，在 o3-mini、o1-mini、DeepSeek-R1 和 QWQ 模型中诱导了计算开销。

> Recent reasoning large language models (LLMs), such as OpenAI o1 and DeepSeek-R1, exhibit strong performance on complex tasks through test-time inference scaling. However, prior studies have shown that these models often incur significant computational costs due to excessive reasoning, such as frequent switching between reasoning trajectories (e.g., underthinking) or redundant reasoning on simple questions (e.g., overthinking). In this work, we expose a novel threat: adversarial inputs can be crafted to exploit excessive reasoning behaviors and substantially increase computational overhead without compromising model utility. Therefore, we propose a novel loss framework consisting of three components: (1) Priority Cross-Entropy Loss, a modification of the standard cross-entropy objective that emphasizes key tokens by leveraging the autoregressive nature of LMs; (2) Excessive Reasoning Loss, which encourages the model to initiate additional reasoning paths during inference; and (3) Delayed Termination Loss, which is designed to extend the reasoning process and defer the generation of final outputs. We optimize and evaluate our attack for the GSM8K and ORCA datasets on DeepSeek-R1-Distill-LLaMA and DeepSeek-R1-Distill-Qwen. Empirical results demonstrate a 3x to 9x increase in reasoning length with comparable utility performance. Furthermore, our crafted adversarial inputs exhibit transferability, inducing computational overhead in o3-mini, o1-mini, DeepSeek-R1, and QWQ models.

[Arxiv](https://arxiv.org/abs/2506.14374)