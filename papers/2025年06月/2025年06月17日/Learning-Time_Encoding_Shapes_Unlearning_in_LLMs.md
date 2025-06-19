# # 学习时间编码塑造LLMs的遗忘机制
学习时间编码塑造LLMs的遗忘机制

发布时间：2025年06月17日

`LLM理论` `隐私保护`

> Learning-Time Encoding Shapes Unlearning in LLMs

# 摘要

> 随着大型语言模型 (LLMs) 在现实世界中的广泛应用，具备``unlearn''能力变得至关重要。这种能力不仅关乎隐私法规，还涉及修正过时或有害的内容。尽管已有研究提出了unlearn基准和算法，并假设训练过程和目标模型固定，但我们通过实证研究发现，学习时间的选择对unlearn事实知识的效果有着重要影响。实验结果显示，使用同义改写描述进行学习能显著提升unlearn性能，但单独删除文本中的一个知识点仍具挑战性。这表明，学习时间的知识编码在实现可靠后摄unlearn中扮演着核心角色。

> As large language models (LLMs) are increasingly deployed in the real world, the ability to ``unlearn'', or remove specific pieces of knowledge post hoc, has become essential for a variety of reasons ranging from privacy regulations to correcting outdated or harmful content. Prior work has proposed unlearning benchmarks and algorithms, and has typically assumed that the training process and the target model are fixed. In this work, we empirically investigate how learning-time choices in knowledge encoding impact the effectiveness of unlearning factual knowledge. Our experiments reveal two key findings: (1) learning with paraphrased descriptions improves unlearning performance and (2) unlearning individual piece of knowledge from a chunk of text is challenging. Our results suggest that learning-time knowledge encoding may play a central role in enabling reliable post-hoc unlearning.

[Arxiv](https://arxiv.org/abs/2506.15076)