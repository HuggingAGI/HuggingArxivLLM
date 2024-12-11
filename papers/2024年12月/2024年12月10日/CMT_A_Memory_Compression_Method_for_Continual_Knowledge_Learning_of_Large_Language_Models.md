# CMT：大型语言模型持续知识学习的内存压缩之法

发布时间：2024年12月10日

`LLM应用` `持续学习`

> CMT: A Memory Compression Method for Continual Knowledge Learning of Large Language Models

# 摘要

> 大型语言模型（LLMs）得适应数据、任务和用户偏好的不断变化。因其规模巨大且训练成本高昂，LLMs 不适宜频繁重训。但为与快速演进的人类知识同步，更新又必不可少。针对这些难题，本文提出压缩记忆训练（CMT）法，这是一种高效且有效的 LLMs 在线适应框架，具备强大的知识留存能力。受人类记忆机制启发，CMT 对新文档进行压缩和信息提取并存入记忆库。回答与这些新文档相关的查询时，模型会从记忆库聚合这些文档记忆，从而更好地回答用户问题。训练和推理过程中，LLM 自身的参数不变，降低了灾难性遗忘的风险。为强化记忆的编码、检索和聚合，我们还进一步提出了三项通用且灵活的新技术，包括记忆感知目标、自匹配和顶部聚合。在三个持续学习数据集（即 StreamingQA、SQuAD 和 ArchivalQA）上开展的大量实验表明，所提方法提升了多个基础 LLMs 的模型适应性和稳健性（比如，在有 Llama-2-7b 的 StreamingQA 中，+4.07 EM 与 +4.19 F1）。

> Large Language Models (LLMs) need to adapt to the continuous changes in data, tasks, and user preferences. Due to their massive size and the high costs associated with training, LLMs are not suitable for frequent retraining. However, updates are necessary to keep them in sync with rapidly evolving human knowledge. To address these challenges, this paper proposes the Compression Memory Training (CMT) method, an efficient and effective online adaptation framework for LLMs that features robust knowledge retention capabilities. Inspired by human memory mechanisms, CMT compresses and extracts information from new documents to be stored in a memory bank. When answering to queries related to these new documents, the model aggregates these document memories from the memory bank to better answer user questions. The parameters of the LLM itself do not change during training and inference, reducing the risk of catastrophic forgetting. To enhance the encoding, retrieval, and aggregation of memory, we further propose three new general and flexible techniques, including memory-aware objective, self-matching and top-aggregation. Extensive experiments conducted on three continual learning datasets (i.e., StreamingQA, SQuAD and ArchivalQA) demonstrate that the proposed method improves model adaptability and robustness across multiple base LLMs (e.g., +4.07 EM & +4.19 F1 in StreamingQA with Llama-2-7b).

[Arxiv](https://arxiv.org/abs/2412.07393)