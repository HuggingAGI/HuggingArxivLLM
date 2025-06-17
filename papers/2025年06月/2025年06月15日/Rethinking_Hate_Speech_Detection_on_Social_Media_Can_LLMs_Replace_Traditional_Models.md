# # 社交媒体仇恨言论检测的新思路：大型语言模型能否取代传统模型？

发布时间：2025年06月15日

`LLM应用` `社交媒体` `内容安全`

> Rethinking Hate Speech Detection on Social Media: Can LLMs Replace Traditional Models?

# 摘要

> 当代社交媒体环境下的仇恨言论检测面临独特挑战，主要源于语言多样性与在线交流的非正式特性。在涉及语言混合、转写以及文化细微差别表达的情境下，这些挑战进一步加剧。尽管微调后的Transformer模型（如BERT）已成为该任务的标准解决方案，但我们主张，近期推出的大型语言模型（LLMs）不仅超越了这些模型的表现，更重新定义了仇恨言论检测的广袤领域。为了支持这一论点，我们引入了IndoHateMix——一个多元且高质量的数据集，该数据集捕捉了印度语境下的印地语-英语语言混合与转写现象，为评估模型在复杂多语言场景下的稳健性提供了一个现实基准，而这些场景往往是现有NLP方法难以应对的。通过广泛的实验，我们发现前沿的LLMs（如LLaMA-3.1）在数据量显著减少的情况下，仍能持续超越针对特定任务的BERT基线模型。凭借其卓越的泛化能力和适应性，LLMs为缓解多样化环境中的在线仇恨提供了一种变革性的方法。这引出了一个问题：未来的研究应优先开发专用模型，还是应致力于构建更为丰富和多样的数据集，以进一步提升LLMs的效果？

> Hate speech detection across contemporary social media presents unique challenges due to linguistic diversity and the informal nature of online discourse. These challenges are further amplified in settings involving code-mixing, transliteration, and culturally nuanced expressions. While fine-tuned transformer models, such as BERT, have become standard for this task, we argue that recent large language models (LLMs) not only surpass them but also redefine the landscape of hate speech detection more broadly. To support this claim, we introduce IndoHateMix, a diverse, high-quality dataset capturing Hindi-English code-mixing and transliteration in the Indian context, providing a realistic benchmark to evaluate model robustness in complex multilingual scenarios where existing NLP methods often struggle. Our extensive experiments show that cutting-edge LLMs (such as LLaMA-3.1) consistently outperform task-specific BERT-based models, even when fine-tuned on significantly less data. With their superior generalization and adaptability, LLMs offer a transformative approach to mitigating online hate in diverse environments. This raises the question of whether future works should prioritize developing specialized models or focus on curating richer and more varied datasets to further enhance the effectiveness of LLMs.

[Arxiv](https://arxiv.org/abs/2506.12744)