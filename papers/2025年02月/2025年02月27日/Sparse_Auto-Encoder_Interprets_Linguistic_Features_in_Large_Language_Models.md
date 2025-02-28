# 稀疏自编码器揭示大语言模型中的语言特征

发布时间：2025年02月27日

`LLM理论` `语言学` `可解释性`

> Sparse Auto-Encoder Interprets Linguistic Features in Large Language Models

# 摘要

> 大型语言模型（LLMs）在需要复杂语言能力的任务中表现出色，例如指代消歧和隐喻识别/生成。尽管LLMs拥有令人印象深刻的性能，但它们在处理和表示语言知识的内部机制仍然 largely 不透明。此前关于语言机制的研究受到粒度粗糙、因果分析不足以及关注范围狭窄的限制。在这项研究中，我们采用稀疏自编码器（SAEs）进行系统全面的因果分析。我们从语音学、音系学、形态学、句法学、语义学和语用学六个维度提取广泛的语言特征。通过构建极小对比数据集和反事实句子数据集，我们提取、评估并干预这些特征。我们引入了两个指标：特征表示置信度（FRC）和特征干预置信度（FIC），以衡量语言特征捕捉和控制语言现象的能力。我们的研究结果揭示了LLMs中语言知识的内在表示，并展示了控制模型输出的潜力。这项工作提供了有力证据，证明LLMs拥有真实的语言知识，并为未来更具可解释性和可控性的语言建模研究奠定了基础。

> Large language models (LLMs) excel in tasks that require complex linguistic abilities, such as reference disambiguation and metaphor recognition/generation. Although LLMs possess impressive capabilities, their internal mechanisms for processing and representing linguistic knowledge remain largely opaque. Previous work on linguistic mechanisms has been limited by coarse granularity, insufficient causal analysis, and a narrow focus. In this study, we present a systematic and comprehensive causal investigation using sparse auto-encoders (SAEs). We extract a wide range of linguistic features from six dimensions: phonetics, phonology, morphology, syntax, semantics, and pragmatics. We extract, evaluate, and intervene on these features by constructing minimal contrast datasets and counterfactual sentence datasets. We introduce two indices-Feature Representation Confidence (FRC) and Feature Intervention Confidence (FIC)-to measure the ability of linguistic features to capture and control linguistic phenomena. Our results reveal inherent representations of linguistic knowledge in LLMs and demonstrate the potential for controlling model outputs. This work provides strong evidence that LLMs possess genuine linguistic knowledge and lays the foundation for more interpretable and controllable language modeling in future research.

[Arxiv](https://arxiv.org/abs/2502.20344)