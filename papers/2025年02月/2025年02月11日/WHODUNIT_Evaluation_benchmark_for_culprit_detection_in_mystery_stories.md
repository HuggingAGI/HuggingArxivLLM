# WHODUNIT：犯罪小说中的罪犯检测评估基准

发布时间：2025年02月11日

`LLM应用` `叙事推理`

> WHODUNIT: Evaluation benchmark for culprit detection in mystery stories

# 摘要

> 我们推出了一个全新数据集 WhoDunIt，旨在评估大型语言模型 (LLM) 在叙事语境下的推理能力。该数据集由开放领域的侦探小说和短篇故事组成，要求 LLM 在阅读并理解故事后找出作案者。

为测试模型的稳定性，我们采用了多种基于角色名称的增强方法，包括原始名称、名称互换以及替换为广为人知的真实或虚构实体。同时，我们还通过不同提示风格探究了提示对推理准确性的影响。

我们使用当前最先进的模型（GPT-4o、GPT-4-turbo 和 GPT-4o-mini）进行了多轮实验，采用多数响应选择以确保结果的可靠性。实验结果表明，尽管 LLM 在原始文本上表现稳定，但面对某些广为人知的名称替换时，准确性会显著下降。该数据集现已公开发布。


> We present a novel data set, WhoDunIt, to assess the deductive reasoning capabilities of large language models (LLM) within narrative contexts. Constructed from open domain mystery novels and short stories, the dataset challenges LLMs to identify the perpetrator after reading and comprehending the story. To evaluate model robustness, we apply a range of character-level name augmentations, including original names, name swaps, and substitutions with well-known real and/or fictional entities from popular discourse. We further use various prompting styles to investigate the influence of prompting on deductive reasoning accuracy.
  We conduct evaluation study with state-of-the-art models, specifically GPT-4o, GPT-4-turbo, and GPT-4o-mini, evaluated through multiple trials with majority response selection to ensure reliability. The results demonstrate that while LLMs perform reliably on unaltered texts, accuracy diminishes with certain name substitutions, particularly those with wide recognition. This dataset is publicly available here.

[Arxiv](https://arxiv.org/abs/2502.07747)