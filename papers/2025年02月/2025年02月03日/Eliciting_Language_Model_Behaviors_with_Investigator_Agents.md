# 利用调查员代理激发语言模型行为

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了语言模型在面对自由文本提示时的行为，特别是如何通过特定的提示诱导出目标行为（如幻觉或有害响应）。研究涉及训练调查员模型来探索提示策略，并揭示了有效提示的多样性。这些内容属于对语言模型行为的理论性研究和分析，因此归类为“LLM理论”。` `人工智能`

> Eliciting Language Model Behaviors with Investigator Agents

# 摘要

> 语言模型在面对自由文本提示时展现出复杂多样的行为，这使得描述其可能输出的空间变得颇具挑战。我们深入研究了行为引发问题，旨在寻找能够从目标语言模型中诱导出特定目标行为（如幻觉或有害响应）的提示。为了在庞大的提示空间中高效导航，我们训练了调查员模型，将随机选择的目标行为映射到引发它们的多样化输出分布，类似于摊销贝叶斯推断。我们通过监督微调、DPO强化学习以及创新的Frank-Wolfe训练目标，迭代地探索多样化的提示策略。我们的调查员模型揭示了一系列有效且易于理解的提示，这些提示成功引发了越狱、幻觉和开放式异常行为，在AdvBench（有害行为）的一个子集上实现了100%的攻击成功率，并达到了85%的幻觉率。

> Language models exhibit complex, diverse behaviors when prompted with free-form text, making it difficult to characterize the space of possible outputs. We study the problem of behavior elicitation, where the goal is to search for prompts that induce specific target behaviors (e.g., hallucinations or harmful responses) from a target language model. To navigate the exponentially large space of possible prompts, we train investigator models to map randomly-chosen target behaviors to a diverse distribution of outputs that elicit them, similar to amortized Bayesian inference. We do this through supervised fine-tuning, reinforcement learning via DPO, and a novel Frank-Wolfe training objective to iteratively discover diverse prompting strategies. Our investigator models surface a variety of effective and human-interpretable prompts leading to jailbreaks, hallucinations, and open-ended aberrant behaviors, obtaining a 100% attack success rate on a subset of AdvBench (Harmful Behaviors) and an 85% hallucination rate.

[Arxiv](https://arxiv.org/abs/2502.01236)