# 马尔可夫链思维：高效数学推理的新方法

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何通过改进思维链（CoT）的方法来提升大型语言模型（LLM）在数学推理任务中的表现。具体来说，它提出了一种新颖的马尔可夫思维链（MCoT），并通过与代码解释器的交互实现了自我校正，从而提高了推理效率和准确性。这些内容属于LLM在实际任务中的应用和改进，因此归类为LLM应用。` `人工智能`

> Markov Chain of Thought for Efficient Mathematical Reasoning

# 摘要

> # 摘要
多步推理的思维链（CoT）通过其逻辑结构和任务特定操作，显著提升了大型语言模型的数学推理能力。然而，随着长CoT的广泛应用，推理步骤的数量常常超出token限制，导致计算需求激增。受人类认知中“推导后简化”的基本逻辑启发，我们将传统的多步CoT重新构想为一种新颖的马尔可夫思维链（MCoT）。在本研究中，我们专注于数学推理任务，将每个推理步骤定义为带有Python代码片段的文本。为了支持更长的推理路径，我们通过与代码解释器的交互实现了自我校正。MCoT的核心思想是将先前的推理步骤压缩为简化问题，从而实现高效的下一步推理，而无需依赖冗长的KV缓存。实验中，我们构建了	exttt{MCoTInstruct}数据集，结果表明MCoT不仅大幅提升了效率，还保持了较高的准确性。尽管仍有诸多问题待解，但这项研究为探索LLMs的长CoT推理能力开辟了新路径。

> Chain of Thought (CoT) of multi-step benefits from the logical structure of the reasoning steps and task-specific actions, significantly enhancing the mathematical reasoning capabilities of large language models. As the prevalence of long CoT, the number of reasoning steps exceeds manageable token limits and leads to higher computational demands. Inspired by the fundamental logic of human cognition, ``derive, then reduce'', we conceptualize the standard multi-step CoT as a novel Markov Chain of Thought (MCoT). In this study, we consider the mathematical reasoning task, defining each reasoning step as text accompanied by a Python code snippet. To facilitate a longer reasoning path, self-correction is enabled through interactions with the code interpreter. Our MCoT aims to compress previous reasoning steps into a simplified question, enabling efficient next-step inference without relying on a lengthy KV cache. In our experiments, we curate the \texttt{MCoTInstruct} dataset, and the empirical results indicate that MCoT not only significantly enhances efficiency but also maintains comparable accuracy. While much remains to be explored, this work paves the way for exploring the long CoT reasoning abilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.17635)