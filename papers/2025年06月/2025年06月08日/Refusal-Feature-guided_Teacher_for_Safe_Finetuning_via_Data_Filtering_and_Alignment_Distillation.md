# # 摘要  
通过数据过滤与对齐蒸馏，基于拒绝特征的教师模型实现安全微调。

发布时间：2025年06月08日

`LLM应用` `AI服务` `模型安全`

> Refusal-Feature-guided Teacher for Safe Finetuning via Data Filtering and Alignment Distillation

# 摘要

> 最近，Google 和 OpenAI 等主要 AI 服务提供商推出了微调即服务（Finetuning-as-a-Service），让用户能够利用自己的数据对大型语言模型（LLMs）进行定制，以满足特定的下游任务需求。然而，当用户数据包含有害提示时，这项服务容易导致 LLM 的安全对齐性能下降。虽然一些先前的研究尝试解决这一问题，但如何从用户数据中根本性地过滤有害数据仍是一个未被探索的问题。我们观察到，从安全对齐的 LLM 中获得的、反映拒绝行为的方向性表示（称为拒绝特征）能够自然地区分有害提示和无害提示。基于这一观察，我们提出了拒绝特征引导的教师模型（ReFT）。我们的 ReFT 模型通过输入提示特征与拒绝特征之间的相似性来识别有害提示。在微调过程中，ReFT 模型作为教师，从用户数据中过滤有害提示，并将对齐知识蒸馏到基础模型中。大量实验表明，基于 ReFT 的微调策略能够有效减少有害输出，提升用户特定任务的微调精度，为在微调即服务中安全可靠地部署 LLM 提供了切实可行的解决方案。

> Recently, major AI service providers such as Google and OpenAI have introduced Finetuning-as-a-Service, which enables users to customize Large Language Models (LLMs) for specific downstream tasks using their own data. However, this service is vulnerable to degradation of LLM safety-alignment when user data contains harmful prompts. While some prior works address this issue, fundamentally filtering harmful data from user data remains unexplored. Motivated by our observation that a directional representation reflecting refusal behavior (called the refusal feature) obtained from safety-aligned LLMs can inherently distinguish between harmful and harmless prompts, we propose the Refusal-Feature-guided Teacher (ReFT). Our ReFT model is trained to identify harmful prompts based on the similarity between input prompt features and its refusal feature. During finetuning, the ReFT model serves as a teacher that filters harmful prompts from user data and distills alignment knowledge into the base model. Extensive experiments demonstrate that our ReFT-based finetuning strategy effectively minimizes harmful outputs and enhances finetuning accuracy for user-specific tasks, offering a practical solution for secure and reliable deployment of LLMs in Finetuning-as-a-Service.

[Arxiv](https://arxiv.org/abs/2506.07356)