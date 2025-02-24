# NOTA：针对视觉大型语言模型的多模态音乐符号理解

发布时间：2025年02月17日

`LLM应用

理由：这篇论文展示了大型语言模型在音乐符号理解领域的应用，特别是在多模态数据处理和跨模态对齐方面的创新。通过开发NotaGPT，他们将LLM应用于音乐领域，证明了其在特定任务中的有效性。因此，归类为LLM应用。` `人工智能`

> NOTA: Multimodal Music Notation Understanding for Visual Large Language Model

# 摘要

> 符号音乐以两种形式呈现：二维的视觉乐谱图像与一维的标准化文本标注序列。尽管大型语言模型在音乐领域潜力巨大，但现有研究主要聚焦于单一模式的符号文本，通用视觉语言模型仍无法理解音乐符号。为此，我们推出了首个大规模多模态音乐符号数据集NOTA，包含1,019,237条记录，覆盖三大区域，涵盖三大任务。基于此，我们开发了专注于音乐符号理解的视觉大型语言模型NotaGPT。在训练中，我们首先通过预对齐阶段实现乐谱图像与ABN文本标注序列的跨模态对齐，随后依次进行基础音乐信息提取与音乐符号分析训练。实验表明，NotaGPT-7B在音乐理解上表现优异，充分证明了NOTA数据集及训练方法的有效性。数据集已开源，地址为https://huggingface.co/datasets/MYTH-Lab/NOTA-dataset。

> Symbolic music is represented in two distinct forms: two-dimensional, visually intuitive score images, and one-dimensional, standardized text annotation sequences. While large language models have shown extraordinary potential in music, current research has primarily focused on unimodal symbol sequence text. Existing general-domain visual language models still lack the ability of music notation understanding. Recognizing this gap, we propose NOTA, the first large-scale comprehensive multimodal music notation dataset. It consists of 1,019,237 records, from 3 regions of the world, and contains 3 tasks. Based on the dataset, we trained NotaGPT, a music notation visual large language model. Specifically, we involve a pre-alignment training phase for cross-modal alignment between the musical notes depicted in music score images and their textual representation in ABC notation. Subsequent training phases focus on foundational music information extraction, followed by training on music notation analysis. Experimental results demonstrate that our NotaGPT-7B achieves significant improvement on music understanding, showcasing the effectiveness of NOTA and the training pipeline. Our datasets are open-sourced at https://huggingface.co/datasets/MYTH-Lab/NOTA-dataset.

[Arxiv](https://arxiv.org/abs/2502.14893)