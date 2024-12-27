# 利用大型语言模型进行多任务分子生成的属性增强指令调整

发布时间：2024年12月23日

`LLM应用` `分子生成`

> Property Enhanced Instruction Tuning for Multi-task Molecule Generation with Large Language Models

# 摘要

> 大型语言模型（LLMs）在问答、机器翻译等各类自然语言处理任务中得到广泛应用。然而，因缺乏有标签数据，且生化特性人工标注难度大，分子生成任务的性能仍受限，在涉及多属性约束的任务中尤甚。在本研究中，我们提出了一个两步框架 PEIT（属性增强指令调整）以改进用于分子相关任务的 LLMs。第一步，我们以文本描述、SMILES 和生化特性作为多模态输入来预训练名为 PEIT-GEN 的模型，通过对齐多模态表示来合成指令数据。第二步，用合成的数据对现有开源 LLMs 进行微调，所得的 PEIT-LLM 能够处理分子标题生成、基于文本的分子生成、分子属性预测以及我们新提出的多约束分子生成任务。实验结果显示，我们预训练的 PEIT-GEN 在分子标题生成方面优于 MolT5 和 BioT5，表明文本描述、结构和生化特性之间的模态对齐良好。此外，PEIT-LLM 在多任务分子生成方面展现出可喜的改进，证明了 PEIT 框架在各类分子任务中的可扩展性。我们在 https://github.com/chenlong164/PEIT 发布了代码、构建的指令数据和模型检查点。

> Large language models (LLMs) are widely applied in various natural language processing tasks such as question answering and machine translation. However, due to the lack of labeled data and the difficulty of manual annotation for biochemical properties, the performance for molecule generation tasks is still limited, especially for tasks involving multi-properties constraints. In this work, we present a two-step framework PEIT (Property Enhanced Instruction Tuning) to improve LLMs for molecular-related tasks. In the first step, we use textual descriptions, SMILES, and biochemical properties as multimodal inputs to pre-train a model called PEIT-GEN, by aligning multi-modal representations to synthesize instruction data. In the second step, we fine-tune existing open-source LLMs with the synthesized data, the resulting PEIT-LLM can handle molecule captioning, text-based molecule generation, molecular property prediction, and our newly proposed multi-constraint molecule generation tasks. Experimental results show that our pre-trained PEIT-GEN outperforms MolT5 and BioT5 in molecule captioning, demonstrating modalities align well between textual descriptions, structures, and biochemical properties. Furthermore, PEIT-LLM shows promising improvements in multi-task molecule generation, proving the scalability of the PEIT framework for various molecular tasks. We release the code, constructed instruction data, and model checkpoints in https://github.com/chenlong164/PEIT.

[Arxiv](https://arxiv.org/abs/2412.18084)