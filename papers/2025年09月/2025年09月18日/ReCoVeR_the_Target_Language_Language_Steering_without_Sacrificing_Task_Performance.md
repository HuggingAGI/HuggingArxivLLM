# ReCoVeR目标语言：不牺牲任务性能的语言调控

发布时间：2025年09月18日

`LLM应用` `基础理论`

> ReCoVeR the Target Language: Language Steering without Sacrificing Task Performance

# 摘要

> 随着大型语言模型（LLMs）的多语言能力不断提升，它们也愈发容易出现语言混淆——即生成的答案语言可能与提示语语言或用户明确要求的回答语言不符。为此，我们提出了ReCoVeR（向量表示中语言混淆减少技术，REducing language COnfusion in VEctor Representations），这是一种基于特定语言引导向量的新颖轻量级方法，专门用于缓解此类混淆。该方法首先借助多平行语料库分离出语言向量，随后通过固定（即无监督）和可训练引导函数，有效利用这些向量实现对LLM的精准引导。我们通过涵盖三个基准测试和18种语言的广泛评估发现，ReCoVeR在单语和跨语言场景下均能有效缓解语言混淆，且与以往的语言引导方法不同，它同时还能保持任务性能。相关数据代码已开源：https://github.com/hSterz/recover。

> As they become increasingly multilingual, Large Language Models (LLMs) exhibit more language confusion, i.e., they tend to generate answers in a language different from the language of the prompt or the answer language explicitly requested by the user. In this work, we propose ReCoVeR (REducing language COnfusion in VEctor Representations), a novel lightweight approach for reducing language confusion based on language-specific steering vectors. We first isolate language vectors with the help of multi-parallel corpus and then effectively leverage those vectors for effective LLM steering via fixed (i.e., unsupervised) as well as trainable steering functions. Our extensive evaluation, encompassing three benchmarks and 18 languages, shows that ReCoVeR effectively mitigates language confusion in both monolingual and cross-lingual setups while at the same time -- and in contrast to prior language steering methods -- retaining task performance. Our data code is available at https://github.com/hSterz/recover.

[Arxiv](https://arxiv.org/abs/2509.14814)