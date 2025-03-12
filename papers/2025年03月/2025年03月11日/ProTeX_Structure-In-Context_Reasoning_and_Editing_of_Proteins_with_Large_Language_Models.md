# ProTeX：基于大型语言模型的蛋白质结构化上下文推理与编辑

发布时间：2025年03月11日

`LLM应用` `蛋白质科学`

> ProTeX: Structure-In-Context Reasoning and Editing of Proteins with Large Language Models

# 摘要

> 大型语言模型在分子科学领域取得了显著进展，特别是在理解和生成功能性小分子方面。这一成功主要得益于分子分词策略的有效性。然而，在蛋白质科学中，尽管氨基酸序列是大型语言模型（LLMs）唯一的分词器，但蛋白质科学中的许多基本挑战本质上是结构依赖性的。由于缺乏感知结构的分词，LLMs在全面生物分子理解和多模态生成方面的能力受到显著限制。

为了解决这些挑战，我们引入了一个创新框架ProTeX。它将蛋白质序列、结构和文本信息分词到一个统一的离散空间中。通过仅采用Next-Token Prediction范式，ProTeX实现了LLMs的联合训练，从而推动了多模态蛋白质推理和生成。ProTeX使通用LLMs能够通过顺序文本输入感知和处理蛋白质结构，利用结构信息作为中间推理组件，并通过顺序文本输出生成或操作结构。

实验结果表明，我们的模型在蛋白质功能预测方面取得了显著改进，与最先进的领域专家模型相比，准确率提高了两倍。ProTeX框架实现了高质量的构象生成和定制化蛋白质设计。首次证明，通过采用大型语言模型领域标准的训练和推理流水线，ProTeX使解码器仅有的LLMs能够有效处理各种蛋白质相关任务。

> Large language models have made remarkable progress in the field of molecular science, particularly in understanding and generating functional small molecules. This success is largely attributed to the effectiveness of molecular tokenization strategies. In protein science, the amino acid sequence serves as the sole tokenizer for LLMs. However, many fundamental challenges in protein science are inherently structure-dependent. The absence of structure-aware tokens significantly limits the capabilities of LLMs for comprehensive biomolecular comprehension and multimodal generation. To address these challenges, we introduce a novel framework, ProTeX, which tokenizes the protein sequences, structures, and textual information into a unified discrete space. This innovative approach enables joint training of the LLM exclusively through the Next-Token Prediction paradigm, facilitating multimodal protein reasoning and generation. ProTeX enables general LLMs to perceive and process protein structures through sequential text input, leverage structural information as intermediate reasoning components, and generate or manipulate structures via sequential text output. Experiments demonstrate that our model achieves significant improvements in protein function prediction, outperforming the state-of-the-art domain expert model with a twofold increase in accuracy. Our framework enables high-quality conformational generation and customizable protein design. For the first time, we demonstrate that by adopting the standard training and inference pipelines from the LLM domain, ProTeX empowers decoder-only LLMs to effectively address diverse spectrum of protein-related tasks.

[Arxiv](https://arxiv.org/abs/2503.08179)