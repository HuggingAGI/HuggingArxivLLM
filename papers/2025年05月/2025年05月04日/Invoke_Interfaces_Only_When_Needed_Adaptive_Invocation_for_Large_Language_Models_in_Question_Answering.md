# 按需调用接口：问答任务中大型语言模型的自适应调用方法

发布时间：2025年05月04日

`LLM应用` `问答系统` `人工智能`

> Invoke Interfaces Only When Needed: Adaptive Invocation for Large Language Models in Question Answering

# 摘要

> 大模型与小模型的协作范式在性能与成本之间找到了一个良好的平衡点，但其核心挑战在于准确识别小型模型在生成过程中出现幻觉时的最佳调用时机。此前的优化尝试主要集中在与推理过程相分离的后处理技术上，导致计算成本高昂且效果有限。本文提出了一种实用的调用评估指标——AttenHScore，该指标能够量化小型模型生成过程中幻觉的累积与传播，持续放大潜在的推理错误。通过动态调整检测阈值，我们实现了对大模型更精准的实时调用。此外，考虑到小模型推理能力的局限性，我们借助不确定性感知的知识重组，帮助它们更好地从不同文本片段中捕捉关键信息。大量实验表明，我们的AttenHScore在提升多轮问答数据集中的实时幻觉检测能力方面优于大多数基线方法，尤其在处理复杂查询时表现突出。此外，我们的策略无需额外的模型训练，并且能够灵活适应各类基于Transformer的模型。

> The collaborative paradigm of large and small language models (LMs) effectively balances performance and cost, yet its pivotal challenge lies in precisely pinpointing the moment of invocation when hallucinations arise in small LMs. Previous optimization efforts primarily focused on post-processing techniques, which were separate from the reasoning process of LMs, resulting in high computational costs and limited effectiveness. In this paper, we propose a practical invocation evaluation metric called AttenHScore, which calculates the accumulation and propagation of hallucinations during the generation process of small LMs, continuously amplifying potential reasoning errors. By dynamically adjusting the detection threshold, we achieve more accurate real-time invocation of large LMs. Additionally, considering the limited reasoning capacity of small LMs, we leverage uncertainty-aware knowledge reorganization to assist them better capture critical information from different text chunks. Extensive experiments reveal that our AttenHScore outperforms most baseline in enhancing real-time hallucination detection capabilities across multiple QA datasets, especially when addressing complex queries. Moreover, our strategies eliminate the need for additional model training and display flexibility in adapting to various transformer-based LMs.

[Arxiv](https://arxiv.org/abs/2505.02311)