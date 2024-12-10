# 关于大型语言模型中学习范式的一项基于内在维度的比较研究

发布时间：2024年12月09日

`LLM理论` `模型学习`

> A Comparative Study of Learning Paradigms in Large Language Models via Intrinsic Dimension

# 摘要

> 大型语言模型（LLMs）在自然语言任务中的性能可借由监督微调（SFT）和上下文学习（ICL）得以提升，二者运作机制各异。监督微调通过在训练数据上最小化损失来更新模型权重，而上下文学习则借助嵌入在提示中的任务示例，且不改变模型参数。本研究运用内在维度（ID）探究这些学习范式对LLMs隐藏表征的影响。我们用ID来估算执行特定自然语言任务时从LLMs提取的表征间的自由度数量。我们先是探究LLM表征的ID在SFT期间的演变情况，以及其因ICL中的示例数量产生的变化。接着，我们对比SFT和ICL所诱导的ID，发现ICL始终诱导出比SFT更高的ID，这表明ICL期间生成的表征处于嵌入空间中更高维的流形里。

> The performance of Large Language Models (LLMs) on natural language tasks can be improved through both supervised fine-tuning (SFT) and in-context learning (ICL), which operate via distinct mechanisms. Supervised fine-tuning updates the model's weights by minimizing loss on training data, whereas in-context learning leverages task demonstrations embedded in the prompt, without changing the model's parameters. This study investigates the effects of these learning paradigms on the hidden representations of LLMs using Intrinsic Dimension (ID). We use ID to estimate the number of degrees of freedom between representations extracted from LLMs as they perform specific natural language tasks. We first explore how the ID of LLM representations evolves during SFT and how it varies due to the number of demonstrations in ICL. We then compare the IDs induced by SFT and ICL and find that ICL consistently induces a higher ID compared to SFT, suggesting that representations generated during ICL reside in higher dimensional manifolds in the embedding space.

[Arxiv](https://arxiv.org/abs/2412.06245)