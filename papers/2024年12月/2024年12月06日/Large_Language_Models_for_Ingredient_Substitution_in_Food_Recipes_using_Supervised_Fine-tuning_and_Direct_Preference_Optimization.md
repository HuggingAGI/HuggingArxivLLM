# 利用大型语言模型进行食品食谱中的成分替换，采用监督微调与直接偏好优化的方法

发布时间：2024年12月06日

`LLM应用`

> Large Language Models for Ingredient Substitution in Food Recipes using Supervised Fine-tuning and Direct Preference Optimization

# 摘要

> 在本文中，我们借助成分替换应对食谱个性化的挑战。我们运用大型语言模型（LLMs）构建了一个旨在预测给定食谱情境中合理替代成分的系统。鉴于针对此任务使用LLMs的情况少之又少，我们开展了一系列广泛的实验，以确定最佳的LLM、提示以及微调设置。我们还进一步尝试了多任务学习、两阶段微调以及直接偏好优化（DPO）等方法。实验基于公开可用的Recipe1MSub语料库进行。经过微调与DPO，Mistral7-Base LLM取得了最佳结果，其Hit@1分数为22.04，超过了同一语料库的强基线。由此，我们认为，此项研究通过利用基于LLM的成分替换，朝着实现个性化和创新性的烹饪体验迈出了关键的一步。

> In this paper, we address the challenge of recipe personalization through ingredient substitution. We make use of Large Language Models (LLMs) to build an ingredient substitution system designed to predict plausible substitute ingredients within a given recipe context. Given that the use of LLMs for this task has been barely done, we carry out an extensive set of experiments to determine the best LLM, prompt, and the fine-tuning setups. We further experiment with methods such as multi-task learning, two-stage fine-tuning, and Direct Preference Optimization (DPO). The experiments are conducted using the publicly available Recipe1MSub corpus. The best results are produced by the Mistral7-Base LLM after fine-tuning and DPO. This result outperforms the strong baseline available for the same corpus with a Hit@1 score of 22.04. Thus we believe that this research represents a significant step towards enabling personalized and creative culinary experiences by utilizing LLM-based ingredient substitution.

[Arxiv](https://arxiv.org/abs/2412.04922)