# 利用在线奥数难题进行LLMs训练与抗污染评估

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了如何利用开源大型语言模型（LLMs）从Art of Problem Solving（AoPS）论坛中提取问答对，生成高质量的数据集AoPS-Instruct，并在此基础上微调LLMs以提升其推理能力。此外，论文还提出了一个自动化流程来构建抗污染的评估集LiveAoPSBench。这些工作都是围绕如何应用LLMs来解决实际问题（如数学推理）展开的，因此属于LLM应用的范畴。`

> Leveraging Online Olympiad-Level Math Problems for LLMs Training and Contamination-Resistant Evaluation

# 摘要

> # 摘要
大型语言模型（LLMs）的突破性进展激发了人们对其解决奥林匹克级别数学问题能力的浓厚兴趣。然而，这些模型的训练和评估受限于可用数据集的规模和质量，因为创建大规模的高级数学问题数据集需要人类专家的巨大投入。此外，现有基准测试容易受到数据污染的影响，导致评估结果不可靠。本文提出了一种自动化流程，利用Art of Problem Solving（AoPS）论坛的丰富资源，该论坛以奥林匹克级别的问题和社区驱动的解决方案为主。通过开源LLMs，我们开发了一种从论坛中提取问答对的方法，生成了AoPS-Instruct数据集，包含超过60万高质量问答对。实验表明，在AoPS-Instruct上微调LLMs显著提升了其在多种基准测试中的推理能力。此外，我们还构建了一个自动化流程，推出了LiveAoPSBench，这是一个带有时间戳的不断更新的评估集，基于最新的论坛数据，为评估LLM性能提供了一个抗污染的基准。值得注意的是，我们发现LLM性能随时间显著下降，这表明其在旧示例上的成功可能源于预训练数据的暴露，而非真正的推理能力。我们的工作为创建和维护大规模、高质量的数学推理数据集提供了一种可扩展的方法，并为LLMs在这一领域的能力和局限性提供了深刻见解。基准和代码可在https://github.com/DSL-Lab/aops获取。

> Advances in Large Language Models (LLMs) have sparked interest in their ability to solve Olympiad-level math problems. However, the training and evaluation of these models are constrained by the limited size and quality of available datasets, as creating large-scale data for such advanced problems requires extensive effort from human experts. In addition, current benchmarks are prone to contamination, leading to unreliable evaluations. In this paper, we present an automated pipeline that leverages the rich resources of the Art of Problem Solving (AoPS) forum, which predominantly features Olympiad-level problems and community-driven solutions. Using open-source LLMs, we develop a method to extract question-answer pairs from the forum, resulting in AoPS-Instruct, a dataset of more than 600,000 high-quality QA pairs. Our experiments demonstrate that fine-tuning LLMs on AoPS-Instruct improves their reasoning abilities across various benchmarks. Moreover, we build an automatic pipeline that introduces LiveAoPSBench, an evolving evaluation set with timestamps, derived from the latest forum data, providing a contamination-resistant benchmark for assessing LLM performance. Notably, we observe a significant decline in LLM performance over time, suggesting their success on older examples may stem from pre-training exposure rather than true reasoning ability. Our work presents a scalable approach to creating and maintaining large-scale, high-quality datasets for advanced math reasoning, offering valuable insights into the capabilities and limitations of LLMs in this domain. Our benchmark and code is available at https://github.com/DSL-Lab/aops

[Arxiv](https://arxiv.org/abs/2501.14275)