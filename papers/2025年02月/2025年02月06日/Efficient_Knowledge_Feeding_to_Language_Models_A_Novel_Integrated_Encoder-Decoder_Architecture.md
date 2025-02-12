# # 语言模型高效知识注入：新型一体化编解码架构

发布时间：2025年02月06日

`RAG` `问答系统`

> Efficient Knowledge Feeding to Language Models: A Novel Integrated Encoder-Decoder Architecture

# 摘要

> 本文提出了一种创新的方法，通过将检索与生成过程整合到统一框架中，实现高效的知识输入，从而提升语言模型（LLMs）的预测性能。尽管检索增强生成（RAG）模型弥补了LLMs训练数据和知识的局限性，但其受限于令牌限制以及对检索系统准确性的依赖。为此，我们提出了基于上下文向量（ICV）的架构，以克服这些挑战。ICV通过利用LLMs的潜在嵌入，重新定义了上下文学习，将其转化为一个捕获关键任务信息的向量。该向量用于调整LLMs的潜在状态，从而在不添加示例的情况下提升生成过程。ICV直接将信息整合到模型中，使其能够更高效地处理这些信息。通过全面的实验评估，我们发现ICV在问答、信息检索和其他任务中均优于标准的上下文学习和微调方法。这一方法不仅缓解了现有RAG模型的局限性，还为处理广泛且多样的数据集提供了更稳健的解决方案。值得注意的是，尽管仅利用了参数的一小部分，我们的ICV增强模型在与LLaMA-3、Gemma和Phi-3等模型的竞争中表现优异，显著降低了计算成本和内存需求。ICV还具有减少提示长度、易于控制、突破令牌限制以及计算效率高等优势，使其成为一种更加高效实用的方法。

> This paper introduces a novel approach to efficiently feeding knowledge to language models (LLMs) during prediction by integrating retrieval and generation processes within a unified framework. While the Retrieval-Augmented Generation (RAG) model addresses gaps in LLMs' training data and knowledge limits, it is hindered by token limit restrictions and dependency on the retrieval system's accuracy. Our proposed architecture incorporates in-context vectors (ICV) to overcome these challenges. ICV recasts in-context learning by using latent embeddings of LLMs to create a vector that captures essential task information. This vector is then used to shift the latent states of the LLM, enhancing the generation process without adding demonstration examples to the prompt. ICV directly integrates information into the model, enabling it to process this information more effectively. Our extensive experimental evaluation demonstrates that ICV outperforms standard in-context learning and fine-tuning across question-answering, information retrieval, and other tasks. This approach mitigates the limitations of current RAG models and offers a more robust solution for handling extensive and diverse datasets. Despite leveraging a fraction of the parameters, our ICV-enhanced model achieves competitive performance against models like LLaMA-3, Gemma, and Phi-3, significantly reducing computational costs and memory requirements. ICV reduces prompt length, is easy to control, surpasses token limitations, and is computationally efficient compared to fine-tuning.

[Arxiv](https://arxiv.org/abs/2502.05233)