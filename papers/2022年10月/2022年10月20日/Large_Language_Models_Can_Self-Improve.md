# 大型语言模型能够实现自我提升

发布时间：2022年10月20日

`LLM应用` `语言模型` `推理能力`

> Large Language Models Can Self-Improve

# 摘要

> 摘要：大型语言模型（LLMs）在各类任务中表现出色。然而，对 LLM 进行微调需要大量监管。另一方面，人类无需外部输入，通过自我思考就能提升推理能力。在本研究中，我们证实 LLM 仅依靠未标记的数据集也能自我改进。我们利用预训练的 LLM，借助思维链提示和自一致性为未标记问题生成“高置信度”的理由增强型答案，并以这些自生成的答案作为目标输出对 LLM 进行微调。结果表明，我们的方法提升了 540B 参数的 LLM 的一般推理能力（GSM8K 上从 74.4%提升至 82.1%，DROP 上从 78.2%提升至 83.0%，OpenBookQA 上从 90.0%提升至 94.4%，ANLI-A3 上从 63.4%提升至 67.9%），达到了领先水平，且无需任何真实标签。我们开展了消融研究，表明对推理进行微调对于自我改进至关重要。

> 
Abstract:Large Language Models (LLMs) have achieved excellent performances in various tasks. However, fine-tuning an LLM requires extensive supervision. Human, on the other hand, may improve their reasoning abilities by self-thinking without external inputs. In this work, we demonstrate that an LLM is also capable of self-improving with only unlabeled datasets. We use a pre-trained LLM to generate "high-confidence" rationale-augmented answers for unlabeled questions using Chain-of-Thought prompting and self-consistency, and fine-tune the LLM using those self-generated solutions as target outputs. We show that our approach improves the general reasoning ability of a 540B-parameter LLM (74.4%->82.1% on GSM8K, 78.2%->83.0% on DROP, 90.0%->94.4% on OpenBookQA, and 63.4%->67.9% on ANLI-A3) and achieves state-of-the-art-level performance, without any ground truth label. We conduct ablation studies and show that fine-tuning on reasoning is critical for self-improvement.
    

[Arxiv](https://arxiv.org/pdf/2210.11610)