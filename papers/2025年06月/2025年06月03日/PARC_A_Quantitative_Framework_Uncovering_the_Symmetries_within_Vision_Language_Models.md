# PARC：一个定量框架，用于揭示视觉语言模型中的对称性。

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了视觉语言模型（VLMs）对提示变化的敏感性，并引入了一个分析框架来评估这种敏感性。研究集中在模型的应用表现及其对提示的响应，属于LLM的应用层面。` `计算机视觉` `人工智能`

> PARC: A Quantitative Framework Uncovering the Symmetries within Vision Language Models

# 摘要

> 视觉语言模型（VLMs）通过响应用户设计的文本提示和视觉输入，被广泛应用于解决现实世界中的问题。VLMs将视觉模态与大型语言模型（LLMs）相结合，而LLMs以其对提示的高度敏感性著称。因此，至关重要的是确定VLMs是否继承了这种对不同提示的不稳定性。为此，我们研究了VLMs对哪些提示变化最敏感，以及哪些VLMs对提示变化最不敏感。为此，我们引入了PARC（通过可靠性和校准进行提示分析），这是一个基于三个核心支柱构建的VLM提示敏感性分析框架：(1)语言和视觉领域中合理的提示变化，(2)一种具有内置保证的新模型可靠性评分，(3)一个校准步骤，使提示变化分析能够跨数据集和提示进行。根据PARC的评估，VLMs在视觉领域中反映了LLM语言提示的敏感性，而最具破坏性的变化会改变预期答案。在22个评估模型中，最出色且稳健的VLMs来自InternVL2家族。我们还发现了一些迹象，表明提示敏感性与训练数据相关。代码将发布在https://github.com/NVlabs/PARC。

> Vision language models (VLMs) respond to user-crafted text prompts and visual inputs, and are applied to numerous real-world problems. VLMs integrate visual modalities with large language models (LLMs), which are well known to be prompt-sensitive. Hence, it is crucial to determine whether VLMs inherit this instability to varying prompts. We therefore investigate which prompt variations VLMs are most sensitive to and which VLMs are most agnostic to prompt variations. To this end, we introduce PARC (Prompt Analysis via Reliability and Calibration), a VLM prompt sensitivity analysis framework built on three pillars: (1) plausible prompt variations in both the language and vision domain, (2) a novel model reliability score with built-in guarantees, and (3) a calibration step that enables dataset- and prompt-spanning prompt variation analysis. Regarding prompt variations, PARC's evaluation shows that VLMs mirror LLM language prompt sensitivity in the vision domain, and most destructive variations change the expected answer. Regarding models, outstandingly robust VLMs among 22 evaluated models come from the InternVL2 family. We further find indications that prompt sensitivity is linked to training data. The code will be at https://github.com/NVlabs/PARC.

[Arxiv](https://arxiv.org/abs/2506.14808)