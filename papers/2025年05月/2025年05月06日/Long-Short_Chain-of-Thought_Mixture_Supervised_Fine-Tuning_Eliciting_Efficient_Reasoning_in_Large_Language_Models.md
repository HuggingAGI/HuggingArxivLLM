# 长-短思维链混合监督微调：激发大型语言模型的高效推理

发布时间：2025年05月06日

`LLM应用` `人工智能` `机器学习`

> Long-Short Chain-of-Thought Mixture Supervised Fine-Tuning Eliciting Efficient Reasoning in Large Language Models

# 摘要

> 大型语言模型的最新进展表明，通过使用从大型推理模型（如 DeepSeek R1）中提炼出的链式推理（CoT）推理数据进行监督微调（SFT），可以有效将推理能力迁移至不具备推理能力的模型。然而，这种微调方法会让模型继承“过度思考”的问题，导致推理过程中产生冗长且冗余的推理链。为了解决这一问题，我们提出了**长-短链式推理混合监督微调（LS-Mixture SFT）**方法，该方法结合了长推理链数据集与其通过结构保留重写获得的短推理链数据集。实验结果表明，采用LS-Mixture SFT方法训练的模型在多个基准测试中平均准确率提高了2.3%，同时将模型的响应长度减少了约47.61%。这项研究提供了一种通过监督微调为不具备推理能力的模型赋予推理能力的方法，同时避免了从教师模型继承的过度思考问题，从而在微调后的模型中实现了高效的推理能力。

> Recent advances in large language models have demonstrated that Supervised Fine-Tuning (SFT) with Chain-of-Thought (CoT) reasoning data distilled from large reasoning models (e.g., DeepSeek R1) can effectively transfer reasoning capabilities to non-reasoning models. However, models fine-tuned with this approach inherit the "overthinking" problem from teacher models, producing verbose and redundant reasoning chains during inference. To address this challenge, we propose \textbf{L}ong-\textbf{S}hort Chain-of-Thought \textbf{Mixture} \textbf{S}upervised \textbf{F}ine-\textbf{T}uning (\textbf{LS-Mixture SFT}), which combines long CoT reasoning dataset with their short counterparts obtained through structure-preserved rewriting. Our experiments demonstrate that models trained using the LS-Mixture SFT method, compared to those trained with direct SFT, achieved an average accuracy improvement of 2.3\% across various benchmarks while substantially reducing model response length by approximately 47.61\%. This work offers an approach to endow non-reasoning models with reasoning capabilities through supervised fine-tuning while avoiding the inherent overthinking problems inherited from teacher models, thereby enabling efficient reasoning in the fine-tuned models.

[Arxiv](https://arxiv.org/abs/2505.03469)