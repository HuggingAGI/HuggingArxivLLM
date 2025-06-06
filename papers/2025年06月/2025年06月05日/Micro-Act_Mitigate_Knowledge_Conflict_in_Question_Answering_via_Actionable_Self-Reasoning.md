# 微行动：通过可操作的自我推理解决问答中的知识冲突

发布时间：2025年06月05日

`RAG` `问答系统`

> Micro-Act: Mitigate Knowledge Conflict in Question Answering via Actionable Self-Reasoning

# 摘要

> 检索增强生成（RAG）系统常常面临知识冲突问题，即检索到的外部知识与大型语言模型（LLMs）的内在知识相矛盾，这对问答（QA）等下游任务的表现产生负面影响。现有方法通常通过简单地并行对比两种知识源来缓解冲突，但这可能让LLMs面对冗余或冗长的上下文，最终影响其识别和解决不一致的能力。为了解决这一问题，我们提出了Micro-Act，一个具有分层动作空间的框架。它能够自动感知上下文复杂度，并自适应地将每个知识源分解为一系列细致的比较。这些比较以可执行的步骤形式呈现，使推理超越表面的上下文。通过在五个基准数据集上的广泛实验，Micro-Act在所有5个数据集和3种冲突类型下（尤其是时间性和语义性冲突类型，所有基线在此类问题上表现显著较差）中，QA准确率较现有最优基线显著提升。更重要的是，Micro-Act在非冲突问题上也表现出稳健的性能，凸显了其在实际RAG应用中的实用价值。
    

> Retrieval-Augmented Generation (RAG) systems commonly suffer from Knowledge Conflicts, where retrieved external knowledge contradicts the inherent, parametric knowledge of large language models (LLMs). It adversely affects performance on downstream tasks such as question answering (QA). Existing approaches often attempt to mitigate conflicts by directly comparing two knowledge sources in a side-by-side manner, but this can overwhelm LLMs with extraneous or lengthy contexts, ultimately hindering their ability to identify and mitigate inconsistencies. To address this issue, we propose Micro-Act a framework with a hierarchical action space that automatically perceives context complexity and adaptively decomposes each knowledge source into a sequence of fine-grained comparisons. These comparisons are represented as actionable steps, enabling reasoning beyond the superficial context. Through extensive experiments on five benchmark datasets, Micro-Act consistently achieves significant increase in QA accuracy over state-of-the-art baselines across all 5 datasets and 3 conflict types, especially in temporal and semantic types where all baselines fail significantly. More importantly, Micro-Act exhibits robust performance on non-conflict questions simultaneously, highlighting its practical value in real-world RAG applications.

[Arxiv](https://arxiv.org/abs/2506.05278)