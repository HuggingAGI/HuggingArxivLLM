# 针对多参与方对话生成的多参与方监督式语言模型微调

发布时间：2024年12月06日

`LLM应用` `多方交流`

> Multi-Party Supervised Fine-tuning of Language Models for Multi-Party Dialogue Generation

# 摘要

> 大型语言模型（LLM）通常被微调用于参与二元或双方对话，难以良好适应多方对话（MPD），这限制了其在多人会议、讨论及日常交流等场景中的应用。此前基于 LLM 的研究主要聚焦于多智能体框架，但其基础 LLM 仍为成对微调。在本研究中，我们针对多方对话数据集为 LLM 设计了一个多方微调框架（MuPaS），并证实这样一个直白的框架能让 LLM 高效且有效地契合多方对话风格。我们还设计了两种训练策略，能将 MuPaS 转化为 MPD 模拟器。大量实验表明，MuPaS 能够达成顶尖的多方响应、更高的下一位发言者预测准确率、更高的人工及自动评估的话语质量，甚至在分布外的场景、主题和角色描述中也能合理生成。MuPaS 框架在 LLM 训练与更复杂的多方应用（如对话生成、虚拟排练或元宇宙）之间架起了桥梁。

> Large Language Models (LLM) are usually fine-tuned to participate in dyadic or two-party dialogues, which can not adapt well to multi-party dialogues (MPD), which hinders their applications in such scenarios including multi-personal meetings, discussions and daily communication. Previous LLM-based researches mainly focus on the multi-agent framework, while their base LLMs are still pairwisely fine-tuned. In this work, we design a multi-party fine-tuning framework (MuPaS) for LLMs on the multi-party dialogue datasets, and prove such a straightforward framework can let the LLM align with the multi-party conversation style efficiently and effectively. We also design two training strategies which can convert MuPaS into the MPD simulator. Substantial experiments show that MuPaS can achieve state-of-the-art multi-party response, higher accuracy of the-next-speaker prediction, higher human and automatic evaluated utterance qualities, and can even generate reasonably with out-of-distribution scene, topic and role descriptions. The MuPaS framework bridges the LLM training with more complicated multi-party applications, such as conversation generation, virtual rehearsal or meta-universe.

[Arxiv](https://arxiv.org/abs/2412.05342)