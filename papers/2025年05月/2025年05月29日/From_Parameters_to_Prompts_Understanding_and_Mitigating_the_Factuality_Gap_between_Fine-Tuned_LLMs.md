# 从参数到提示：理解并缓解微调 LLM 的事实性差距

发布时间：2025年05月29日

`LLM理论` `知识管理` `知识图谱`

> From Parameters to Prompts: Understanding and Mitigating the Factuality Gap between Fine-Tuned LLMs

# 摘要

> 事实知识抽取旨在显式提取预训练语言模型中的知识参数，用于下游任务。尽管先前研究探讨了监督微调数据对大型语言模型事实性的影响，但其机制尚不明确。我们通过系统性实验重新审视了这一影响，重点关注微调已知与未知知识时的事实性差距。研究发现，这一差距可通过推理阶段的处理缓解，无论是出分布（OOD）设置还是合适的上下文学习（ICL）提示（如少量样本学习和思维链（CoT））。我们从知识图谱角度进行理论证明，表明测试时提示可能减弱甚至盖过微调数据影响，主导知识抽取过程。研究结果揭示了微调数据与测试时提示的互动关系，表明ICL能有效弥补微调数据不足，并强调了重新考虑将ICL提示作为评估微调数据选择方法有效性的必要性。

> Factual knowledge extraction aims to explicitly extract knowledge parameterized in pre-trained language models for application in downstream tasks. While prior work has been investigating the impact of supervised fine-tuning data on the factuality of large language models (LLMs), its mechanism remains poorly understood. We revisit this impact through systematic experiments, with a particular focus on the factuality gap that arises when fine-tuning on known versus unknown knowledge. Our findings show that this gap can be mitigated at the inference stage, either under out-of-distribution (OOD) settings or by using appropriate in-context learning (ICL) prompts (i.e., few-shot learning and Chain of Thought (CoT)). We prove this phenomenon theoretically from the perspective of knowledge graphs, showing that the test-time prompt may diminish or even overshadow the impact of fine-tuning data and play a dominant role in knowledge extraction. Ultimately, our results shed light on the interaction between finetuning data and test-time prompt, demonstrating that ICL can effectively compensate for shortcomings in fine-tuning data, and highlighting the need to reconsider the use of ICL prompting as a means to evaluate the effectiveness of fine-tuning data selection methods.

[Arxiv](https://arxiv.org/abs/2505.23410)