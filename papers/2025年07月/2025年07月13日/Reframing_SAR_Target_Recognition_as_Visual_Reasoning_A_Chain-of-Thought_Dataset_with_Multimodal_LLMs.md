# 将 SAR 目标识别重新定义为视觉推理问题，构建了一个结合多模态 LLM 的思维链数据集

发布时间：2025年07月13日

`LLM应用

理由：这篇论文探讨了将多模态大型语言模型（MLLMs）应用于合成孔径雷达（SAR）图像识别中的方法和效果，属于大型语言模型的实际应用研究。` `计算机视觉`

> Reframing SAR Target Recognition as Visual Reasoning: A Chain-of-Thought Dataset with Multimodal LLMs

# 摘要

> 合成孔径雷达 (SAR) 图像识别一直面临传统方法难以克服的挑战，如纹理缺失、噪声干扰和目标边界模糊。本研究另辟蹊径，将 SAR 目标识别转化为多模态推理任务。我们借助 GPT-4o 等多模态大型语言模型 (MLLMs)，通过候选类别引导和链式思维 (CoT) 推理，实现了基于 SAR 图像的目标分类。基于 FAIR-CSAR 基准，我们创建了一个新数据集，整合了原始 SAR 图像、结构化标注、候选标签及推理链。实验结果表明，MLLMs 在绝大多数情况下能生成逻辑清晰且易于理解的推理结果。我们的分析揭示了 MLLMs 在 SAR 图像解读中的优势与局限，并通过案例分析深入探讨了模型行为。这项研究不仅验证了将 MLLMs 应用于 SAR 分析的可行性，更为未来 SAR 视觉推理研究奠定了基础。

> In the context of Synthetic Aperture Radar (SAR) image recognition, traditional methods often struggle with the intrinsic limitations of SAR data, such as weak texture, high noise, and ambiguous object boundaries. This work explores a novel perspective by reformulating SAR target recognition as a multimodal reasoning task. We leverage multimodal large language models (MLLMs), specifically GPT-4o, to perform target classification based on SAR imagery, guided by candidate categories and enhanced with Chain-of-Thought (CoT) reasoning. A new dataset is constructed based on the FAIR-CSAR benchmark, comprising raw SAR images, structured target annotations, candidate label sets, and GPT-generated CoT reasoning chains. Experimental results show that the MLLMs are capable of generating logically coherent and interpretable inferences in most scenarios. Our analysis highlights both the strengths and current limitations of MLLMs in interpreting SAR imagery, and we provide detailed insights into model behavior through failure case analysis. This work demonstrates the feasibility of incorporating MLLMs into SAR analysis pipelines and establishes a foundation for future research in SAR-oriented visual reasoning.

[Arxiv](https://arxiv.org/abs/2507.09535)