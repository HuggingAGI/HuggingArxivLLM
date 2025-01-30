# Tonguescape: 语言模型如何理解元音发音

发布时间：2025年01月29日

`LLM应用

**解释**：这篇论文探讨了语言模型（LMs）在理解元音发音机制方面的应用，特别是通过视觉信息（如实时MRI数据）来理解舌头位置与元音之间的关系。虽然论文涉及多模态LMs，但主要关注的是LMs在特定应用场景（元音发音机制）中的表现，因此归类为“LLM应用”。` `语言学`

> Tonguescape: Exploring Language Models Understanding of Vowel Articulation

# 摘要

> 元音的核心特征在于舌头的位置。人类通过自身经验和MRI等客观观察手段，揭示了元音发音的奥秘。凭借这些知识，我们能够解释舌头位置与元音之间的关系，这对语言学习者掌握发音大有裨益。由于语言模型（LMs）在大量语言学和医学数据上训练，初步研究表明，LMs能够解释元音的发音机制。然而，多模态LMs（如视觉LMs）是否能够将文本信息与视觉信息对齐，仍是一个未解之谜。本研究从实时MRI数据集中构建了视频和图像数据集，探讨了LMs是否能够基于视觉信息理解元音发音的舌头位置。研究发现，LMs在提供参考示例时表现出理解元音和舌头位置的潜力，但在缺乏参考示例时则显得力不从心。数据集构建代码已开源在GitHub上。

> Vowels are primarily characterized by tongue position. Humans have discovered these features of vowel articulation through their own experience and explicit objective observation such as using MRI. With this knowledge and our experience, we can explain and understand the relationship between tongue positions and vowels, and this knowledge is helpful for language learners to learn pronunciation. Since language models (LMs) are trained on a large amount of data that includes linguistic and medical fields, our preliminary studies indicate that an LM is able to explain the pronunciation mechanisms of vowels. However, it is unclear whether multi-modal LMs, such as vision LMs, align textual information with visual information. One question arises: do LMs associate real tongue positions with vowel articulation? In this study, we created video and image datasets from the existing real-time MRI dataset and investigated whether LMs can understand vowel articulation based on tongue positions using vision-based information. Our findings suggest that LMs exhibit potential for understanding vowels and tongue positions when reference examples are provided while they have difficulties without them. Our code for dataset building is available on GitHub.

[Arxiv](https://arxiv.org/abs/2501.17643)