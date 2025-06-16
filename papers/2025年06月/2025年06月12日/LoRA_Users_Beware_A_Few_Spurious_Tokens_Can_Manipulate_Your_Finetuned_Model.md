# 使用 LoRA 的用户请注意：只需几个虚假标记，就能操控你的微调模型。

发布时间：2025年06月12日

`LLM应用`

> LoRA Users Beware: A Few Spurious Tokens Can Manipulate Your Finetuned Model

# 摘要

> 参数高效微调（PEFT）如低秩适配（LoRA）为大型语言模型（LLMs）对齐下游任务提供了高效的解决方案。然而，由于效率一直是主要关注点，模型潜在的灾难性故障却鲜受关注。我们发现PEFT存在一个严重问题：它会让模型寻找捷径来完成微调任务。当下游任务类别与少量token（例如每个提示仅一个token）相关联时，PEFT会让模型过度依赖这些token做决策。这些虚假token可能因数据清洗错误而偶然出现，但也为恶意行为者通过无缝虚假token注入（SSTI）控制模型行为提供了可乘之机。在SSTI中，数据集创建者注入少量与下游类别相关的token。在测试时，只需注入这些少量token即可完全控制微调后的LLM行为。我们对三个模型家族（Snowflake Arctic、Apple OpenELM 和 Meta LLaMA-3）和四个多样化数据集（IMDB、金融分类、常识问答和简历偏见）进行了SSTI实验。结果令人震惊：仅需一个SSTI token就可完全改变模型决策；轻量级SSTI的虚假依赖程度与LoRA秩成正比；激进SSTI下，较大的LoRA秩值更优，因为它能提升模型对非虚假token的关注，从而增强模型鲁棒性。

> Parameter Efficient FineTuning (PEFT), such as Low-Rank Adaptation (LoRA), aligns pre-trained Large Language Models (LLMs) to particular downstream tasks in a resource-efficient manner. Because efficiency has been the main metric of progress, very little attention has been put in understanding possible catastrophic failures. We uncover one such failure: PEFT encourages a model to search for shortcut solutions to solve its fine-tuning tasks. When very small amount of tokens, e.g., one token per prompt, are correlated with downstream task classes, PEFT makes any pretrained model rely predominantly on that token for decision making. While such spurious tokens may emerge accidentally from incorrect data cleaning, it also opens opportunities for malevolent parties to control a model's behavior from Seamless Spurious Token Injection (SSTI). In SSTI, a small amount of tokens correlated with downstream classes are injected by the dataset creators. At test time, the finetuned LLM's behavior can be controlled solely by injecting those few tokens. We apply SSTI across models from three families (Snowflake Arctic, Apple OpenELM, and Meta LLaMA-3) and four diverse datasets (IMDB, Financial Classification, CommonSense QA, and Bias in Bios). Our findings reveal three astonishing behaviors. First, as few as a single token of SSTI is sufficient to steer a model's decision making. Second, for light SSTI, the reliance on spurious tokens is proportional to the LoRA rank. Lastly, with aggressive SSTI, larger LoRA rank values become preferable to small rank values as it makes the model attend to non-spurious tokens, hence improving robustness.

[Arxiv](https://arxiv.org/abs/2506.11402)