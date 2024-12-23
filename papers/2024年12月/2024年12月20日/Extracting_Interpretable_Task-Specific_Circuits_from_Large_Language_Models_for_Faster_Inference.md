# 从大型语言模型里提取出可解释的特定任务电路，以加快推理速度

发布时间：2024年12月20日

`LLM应用` `模型压缩`

> Extracting Interpretable Task-Specific Circuits from Large Language Models for Faster Inference

# 摘要

> 大型语言模型（LLMs）在众多任务中展现出了非凡的性能。然而，LLMs 的规模持续增大，这给其在计算资源受限的环境中的应用带来了阻碍。另一方面，尽管它们具备通用能力，但在很多情况下，仅执行一项特定任务，其他能力都成了多余和浪费。这引发了我们这样的思考：能否从 LLM 中抽取能以更快、独立的方式完成特定任务的最小子集？关于机械可解释性（MI）的最新研究表明，特定任务由组件或电路的局部子集来执行。但目前用于识别电路的技术无法用于提取它以作独立使用。在本研究中，我们提出了一种创新的方法，能自动提取出可正确执行目标任务的 LLM 子集，无需额外训练，且只需少量数据样本。我们在不同任务中对该方法进行了评估，结果显示所得模型（一）规模大幅缩小，参数数量减少多达 82.77%；（二）更具可解释性，因为它们聚焦于执行特定任务的电路，所以能够运用 MI 技术加以理解。

> Large Language Models (LLMs) have shown impressive performance across a wide range of tasks. However, the size of LLMs is steadily increasing, hindering their application on computationally constrained environments. On the other hand, despite their general capabilities, there are many situations where only one specific task is performed, rendering all other capabilities unnecessary and wasteful. This leads us to the following question: Is it possible to extract the minimal subset from an LLM that is able to perform a specific task in a faster, standalone manner? Recent works on Mechanistic Interpretability (MI) have shown that specific tasks are performed by a localized subset of components, or circuit. However, current techniques used to identify the circuit cannot be used to extract it for its standalone usage. In this work, we propose a novel approach to automatically extract the subset of the LLM that properly performs a targeted task requiring no additional training and a small amount of data samples. We evaluate our approach on different tasks and show that the resulting models are (i) considerably smaller, reducing the number of parameters up to 82.77% and (ii) more interpretable, as they focus on the circuit that is used to carry out the specific task, and can therefore be understood using MI techniques.

[Arxiv](https://arxiv.org/abs/2412.15750)