# 从答案到理由：自我对齐的多模态推理与答案导向的思维链

发布时间：2025年07月01日

`LLM理论` `人工智能` `推理框架`

> From Answers to Rationales: Self-Aligning Multimodal Reasoning with Answer-Oriented Chain-of-Thought

# 摘要

> 长期以来，实现多模态大语言模型（MLLMs）的类人推理能力一直是研究的目标。然而，现有方法主要聚焦于生成正面推理路径，却忽视了负面推理路径在训练模型识别错误推理模式中的关键作用。为弥补这一研究空白，我们提出了一种全新的框架：	extbf{S}elf-Aligning 	extbf{M}ultimodal Reasoning with 	extbf{A}nswer-O	extbf{r}iented Chain-of-	extbf{Th}ought（SMART）。该框架通过以答案为导向的链式思考（AoT）提示，使模型能够自动生成高质量的正负面推理路径，并通过自我对齐机制不断提升其推理能力。受人类解决基于证明问题的策略启发，AoT以答案为引导，帮助模型提取连接问题与答案的关键视觉信息。当提供真实答案时，模型会生成强有力的正面推理路径；而当正确答案被误导性替代答案取代时，模型则会产生一个错误但极具说服力的推理路径，作为区分性的负面推理路径。与使用手动标注数据训练的模型相比，基于AoT生成数据训练的模型展现出更卓越的推理能力。这表明，我们可以利用改进后的模型生成更高质量的偏好数据，从而进一步优化模型性能。因此，SMART框架建立了一种迭代生成与优化的方法，持续提升模型的推理能力。实验结果表明，无论模型架构、参数规模还是预训练数据集如何，SMART框架都能显著提升各种MLLMs的性能。代码、数据集和模型将被公开发布。

> Achieving human-like reasoning capabilities in Multimodal Large Language Models (MLLMs) has long been a goal. Current methodologies primarily focus on synthesizing positive rationales, while overlooking the critical role of negative rationales in training models to discern flawed reasoning patterns. To address this gap, we propose a novel framework: \textbf{S}elf-Aligning \textbf{M}ultimodal Reasoning with \textbf{A}nswer-O\textbf{r}iented Chain-of-\textbf{T}hought (SMART). This framework enables models to utilize AoT-Oriented Chain-of-Thought (AoT) prompts to automatically generate high-quality positive and negative reasoning paths, followed by self-alignment to enhance their reasoning abilities. Inspired by human strategies for solving proof-based problems, AoT uses answers as a guide to help the model extract critical visual information that links questions and answers. When provided with ground truth answers, the model produces strong positive rationales. Conversely, when correct answers are replaced with misleading alternatives, the model generates an erroneous yet compelling reasoning path, serving as a form of discriminative negative rationale. Models trained with AoT-generated data outperform those trained on manually annotated datasets, demonstrating superior reasoning capabilities. This encourages the use of improved models to generate higher-quality preference data for further optimization. Consequently, SMART establishes an iterative generation-optimization method that continually enhances the model's reasoning skills. Experiments indicate that the SMART framework significantly improves various MLLMs, regardless of model architecture, parameter size, or pre-training dataset. The code, datasets, and models will be released.

[Arxiv](https://arxiv.org/abs/2507.02984)