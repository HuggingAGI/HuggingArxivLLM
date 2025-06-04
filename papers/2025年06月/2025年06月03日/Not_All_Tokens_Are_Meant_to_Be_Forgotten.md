# 并非所有token都需要被遗忘

发布时间：2025年06月03日

`LLM理论` `人工智能` `隐私保护`

> Not All Tokens Are Meant to Be Forgotten

# 摘要

> 大型语言模型（LLMs）在大规模文本语料库上预训练后，展现出令人惊叹的人类水平语言理解、推理和决策能力。然而，这些模型容易记忆私人或版权内容等不必要信息，引发隐私和法律问题。无学习（Unlearning）作为解决方案出现，但现有方法面临过度遗忘的挑战。这是因为它们在遗忘样本中不加选择地抑制所有令牌的生成，导致模型效用严重下降。为解决这一问题，我们提出了目标信息遗忘（TIF）框架，包含两个关键组件：（1）一个灵活的目标信息标识器，用于区分遗忘样本中的不需要的单词（UW）和通用单词（GW）；（2）一种创新的目标偏好优化方法，利用Logit偏好损失来遗忘与UW相关的不需要信息，同时通过保留损失来保持GW中的通用信息，从而有效提升无学习效果，同时减少效用损失。在TOFU和MUSE基准上的大量实验表明，TIF框架显著提升了无学习效果，保留了模型效用，并达到了当前最优水平。

> Large Language Models (LLMs), pre-trained on massive text corpora, exhibit remarkable human-level language understanding, reasoning, and decision-making abilities. However, they tend to memorize unwanted information, such as private or copyrighted content, raising significant privacy and legal concerns. Unlearning has emerged as a promising solution, but existing methods face a significant challenge of over-forgetting. This issue arises because they indiscriminately suppress the generation of all the tokens in forget samples, leading to a substantial loss of model utility. To overcome this challenge, we introduce the Targeted Information Forgetting (TIF) framework, which consists of (1) a flexible targeted information identifier designed to differentiate between unwanted words (UW) and general words (GW) in the forget samples, and (2) a novel Targeted Preference Optimization approach that leverages Logit Preference Loss to unlearn unwanted information associated with UW and Preservation Loss to retain general information in GW, effectively improving the unlearning process while mitigating utility degradation. Extensive experiments on the TOFU and MUSE benchmarks demonstrate that the proposed TIF framework enhances unlearning effectiveness while preserving model utility and achieving state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2506.03142)