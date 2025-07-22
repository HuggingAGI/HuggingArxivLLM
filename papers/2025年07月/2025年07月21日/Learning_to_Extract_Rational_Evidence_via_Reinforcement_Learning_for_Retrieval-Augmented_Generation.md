# 通过强化学习学习提取合理依据，用于检索增强生成

发布时间：2025年07月21日

`RAG` `大型语言模型` `问答系统`

> Learning to Extract Rational Evidence via Reinforcement Learning for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）显著提升了大型语言模型（LLMs）的生成准确性。然而，检索噪声对生成质量的影响不容忽视，亟需开发去噪机制。传统方法在提取证据时缺乏明确的思考过程，这可能导致关键线索被过滤，同时面临泛化能力的挑战。为此，我们提出LEAR方法，通过分步策略实现理性证据提取：首先明确推理以识别检索内容中的潜在线索，然后有意识地提取证据以避免遗漏任何有助于回答问题的关键线索。具体而言，我们将证据推理与证据提取整合为统一响应，实现端到端训练；采用知识令牌掩码进行解耦，分别生成基于推理和基于提取的答案；并设计了三种可验证的奖励函数，包括答案、长度和格式，通过策略优化算法更新模型。在三个基准数据集上的广泛实验表明，LEAR能够提供简洁且高质量的证据，显著提升下游任务的准确性，并推动其在在线RAG系统中的有效应用。

> Retrieval-Augmented Generation (RAG) effectively improves the accuracy of Large Language Models (LLMs). However, retrieval noises significantly impact the quality of LLMs' generation, necessitating the development of denoising mechanisms. Previous methods extract evidence straightforwardly without explicit thinking, which risks filtering out key clues and struggles with generalization. To this end, we propose LEAR, which learns to extract rational evidence by (1) explicitly reasoning to identify potential cues within retrieval contents first, and then (2) consciously extracting to avoid omitting any key cues helpful for answering questions. Specifically, we frame evidence reasoning and evidence extraction into one unified response for end-to-end training; apply knowledge token masks for disentanglement to derive reasoning-based and extraction-based answers; and devise three types of verifiable reward functions, including answer, length, and format, to update the model via the policy optimization algorithm. Extensive experiments on three benchmark datasets show the effectiveness of LEAR, providing compact and high-quality evidence, improving the accuracy of downstream tasks, and promoting effective application in online RAG systems.

[Arxiv](https://arxiv.org/abs/2507.15586)