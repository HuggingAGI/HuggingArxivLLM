# EvoLlama: 利用多模态结构与序列表示提升LLMs的蛋白质理解能力

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要讨论了如何将蛋白质编码器与大型语言模型（LLM）结合，以增强对蛋白质的理解。具体来说，作者提出了一个名为EvoLlama的多模态框架，该框架整合了基于结构的编码器、基于序列的蛋白质编码器和LLM，并在蛋白质理解和属性预测任务上进行了实验。这些工作属于将LLM应用于特定领域（蛋白质理解）的实际应用，因此应归类为LLM应用。` `生物信息学` `蛋白质研究`

> EvoLlama: Enhancing LLMs' Understanding of Proteins via Multimodal Structure and Sequence Representations

# 摘要

> # 摘要
当前用于蛋白质理解的大型语言模型（LLMs）主要将氨基酸序列视为文本模态。与此同时，蛋白质语言模型（PLMs），如ESM-2，已从自然蛋白质序列中学习了大量序列进化知识。此外，基于结构的编码器如ProteinMPNN通过图神经网络学习蛋白质的结构信息。然而，将蛋白质编码器整合到LLMs中是否能增强其对蛋白质的理解尚未被探索。为此，我们提出了EvoLlama，一个多模态框架，将基于结构的编码器、基于序列的蛋白质编码器和LLM连接起来以理解蛋白质。EvoLlama包括ProteinMPNN结构编码器、ESM-2蛋白质序列编码器、多模态投影器（用于对齐蛋白质和文本表示）以及Llama-3文本解码器。我们在面向蛋白质的指令和通过自然语言指令模板表达的蛋白质属性预测数据集上对EvoLlama进行了微调。实验表明，EvoLlama的蛋白质理解能力显著增强，在零-shot设置下平均优于其他面向蛋白质的微调LLMs 1%-8%，并在有监督微调下平均超过最先进的基线6%。在蛋白质属性预测数据集上，我们的方法取得了与最先进的特定任务基线相竞争的结果。我们将在未来的版本中发布代码。

> Current Large Language Models (LLMs) for understanding proteins primarily treats amino acid sequences as a text modality. Meanwhile, Protein Language Models (PLMs), such as ESM-2, have learned massive sequential evolutionary knowledge from the universe of natural protein sequences. Furthermore, structure-based encoders like ProteinMPNN learn the structural information of proteins through Graph Neural Networks. However, whether the incorporation of protein encoders can enhance the protein understanding of LLMs has not been explored. To bridge this gap, we propose EvoLlama, a multimodal framework that connects a structure-based encoder, a sequence-based protein encoder and an LLM for protein understanding. EvoLlama consists of a ProteinMPNN structure encoder, an ESM-2 protein sequence encoder, a multimodal projector to align protein and text representations and a Llama-3 text decoder. To train EvoLlama, we fine-tune it on protein-oriented instructions and protein property prediction datasets verbalized via natural language instruction templates. Our experiments show that EvoLlama's protein understanding capabilities have been significantly enhanced, outperforming other fine-tuned protein-oriented LLMs in zero-shot settings by an average of 1%-8% and surpassing the state-of-the-art baseline with supervised fine-tuning by an average of 6%. On protein property prediction datasets, our approach achieves promising results that are competitive with state-of-the-art task-specific baselines. We will release our code in a future version.

[Arxiv](https://arxiv.org/abs/2412.11618)