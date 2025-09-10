# PLaID++：面向靶向无机材料设计的偏好对齐语言模型

发布时间：2025年09月08日

`LLM应用` `能源与环保`

> PLaID++: A Preference Aligned Language Model for Targeted Inorganic Materials Design

# 摘要

> 新型材料的发现对太阳能电池、电池及碳捕获等技术的进步至关重要。然而，新材料的研发受限于缓慢且成本高昂的试错流程。为加速这一进程，我们提出PLaID++——一款针对稳定且属性引导的晶体生成任务微调的大型语言模型（LLM）。我们通过微调Qwen-2.5 7B模型，采用全新的基于Wyckoff符号的文本表示方法生成晶体结构。研究表明，借助基于直接偏好优化（DPO）的强化学习技术，可有效引导生成过程，并能根据稳定性、新颖性及空间群对生成结构进行分类。通过将对称性约束直接编码为文本，并引导模型输出至目标化学空间，PLaID++生成的结构具备热力学稳定性、独特性和新颖性，其生成效率较以往方法提升约【数学公式】，同时能定向生成具有特定空间群特性的结构。实验结果表明，迭代DPO方法成效显著：与单纯微调相比，在无条件生成和空间群条件生成任务中，性能分别提升约【数学公式】和【数学公式】。本研究证明了将自然语言处理中的后训练技术应用于材料设计的潜力，为定向、高效的新型材料发现奠定了基础。

> Discovering novel materials is critical for technological advancements such as solar cells, batteries, and carbon capture. However, the development of new materials is constrained by a slow and expensive trial-and-error process. To accelerate this pipeline, we introduce PLaID++, a Large Language Model (LLM) fine-tuned for stable and property-guided crystal generation. We fine-tune Qwen-2.5 7B to generate crystal structures using a novel Wyckoff-based text representation. We show that generation can be effectively guided with a reinforcement learning technique based on Direct Preference Optimization (DPO), with sampled structures categorized by their stability, novelty, and space group. By encoding symmetry constraints directly into text and guiding model outputs towards desirable chemical space, PLaID++ generates structures that are thermodynamically stable, unique, and novel at a $\sim$50\% greater rate than prior methods and conditionally generates structures with desired space group properties. Our experiments highlight the effectiveness of iterative DPO, achieving $\sim$115\% and $\sim$50\% improvements in unconditional and space group conditioned generation, respectively, compared to fine-tuning alone. Our work demonstrates the potential of adapting post-training techniques from natural language processing to materials design, paving the way for targeted and efficient discovery of novel materials.

[Arxiv](https://arxiv.org/abs/2509.07150)