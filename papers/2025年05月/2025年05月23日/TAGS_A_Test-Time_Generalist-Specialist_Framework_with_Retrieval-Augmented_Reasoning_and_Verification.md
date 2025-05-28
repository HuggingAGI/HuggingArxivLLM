# TAGS：测试时通用-专用框架，结合检索增强推理和验证

发布时间：2025年05月23日

`LLM应用` `问答系统`

> TAGS: A Test-Time Generalist-Specialist Framework with Retrieval-Augmented Reasoning and Verification

# 摘要

> 思维链提示等技术近期大幅提升了大型语言模型在零样本医学推理中的性能。然而，基于提示的方法效果往往浅显且不稳定，而微调后的医学领域大型语言模型在面对分布偏移和未见过的临床场景时表现欠佳。为了解决这些问题，我们提出了一种无需微调或参数更新的测试时框架TAGS，该框架巧妙结合通用模型与领域专家模型，提供互补视角。为了支持这一推理过程，我们设计了两个辅助模块：一种层次化的检索机制，通过语义和推理层面的相似性选择示例，提供多尺度的样例；以及一个可靠性评分器，评估推理一致性以指导最终答案的聚合。TAGS在九个医学问答基准测试中表现出色，将GPT-4o的准确率提升了13.8%，DeepSeek-R1提升了16.8%，并将一个基础7B模型的准确率从14.1%提升至23.9%。这些结果超越了多个经过微调的医学领域大型语言模型，且无需任何参数更新。代码将在https://github.com/JianghaoWu/TAGS上公开。

> Recent advances such as Chain-of-Thought prompting have significantly improved large language models (LLMs) in zero-shot medical reasoning. However, prompting-based methods often remain shallow and unstable, while fine-tuned medical LLMs suffer from poor generalization under distribution shifts and limited adaptability to unseen clinical scenarios. To address these limitations, we present TAGS, a test-time framework that combines a broadly capable generalist with a domain-specific specialist to offer complementary perspectives without any model fine-tuning or parameter updates. To support this generalist-specialist reasoning process, we introduce two auxiliary modules: a hierarchical retrieval mechanism that provides multi-scale exemplars by selecting examples based on both semantic and rationale-level similarity, and a reliability scorer that evaluates reasoning consistency to guide final answer aggregation. TAGS achieves strong performance across nine MedQA benchmarks, boosting GPT-4o accuracy by 13.8%, DeepSeek-R1 by 16.8%, and improving a vanilla 7B model from 14.1% to 23.9%. These results surpass several fine-tuned medical LLMs, without any parameter updates. The code will be available at https://github.com/JianghaoWu/TAGS.

[Arxiv](https://arxiv.org/abs/2505.18283)