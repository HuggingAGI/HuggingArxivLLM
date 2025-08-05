# MLP记忆：借助预训练检索器的外部记忆实现语言建模

发布时间：2025年08月03日

`RAG` `知识密集型任务`

> MLP Memory: Language Modeling with Retriever-pretrained External Memory

# 摘要

> 尽管现代解码器型大型语言模型（LLMs）在多个领域表现出色，但幻觉问题在生成文本中日益突出，限制了其在知识密集型任务中的应用。针对这一问题，检索增强生成（RAG）提供了一种解决方案，但检索器的非参数特性限制了其与LLM的深度交互。在本研究中，我们提出了一种创新方法，通过预训练的可微外部记忆模块将记忆功能从LLM解码器中分离出来。该外部记忆是一个多层感知机（MLP），通过模仿整个预训练数据集上的检索器行为进行预训练。我们的最终架构由一个变压器解码器和一个外部MLP记忆模块组成，分别在语言建模和检索器模仿上进行预训练，展现出强大的困惑度和下游任务性能。实验结果表明，与仅解码器型模型相比，我们的架构在WikiText-103和Web数据集上分别实现了17.5%和24.1%的性能提升，同时在不导致过拟合的情况下受益于额外的训练。我们在三个幻觉基准测试和九个记忆密集型任务中展示了更优性能。此外，我们的方法在速度上比$k$NN-LM（500M tokens）快了【数学公式】倍，并且推理速度比仅解码器型模型快1.3倍。与$k$NN-LM不同，我们的MLP记忆模块增强了策略问答（StrategyQA）的表现。未来，我们将开源我们的代码和模型。

> While modern decoder-only LLMs achieve superior performance across various domains, hallucinations have risen to be a common problem in their generated text, hindering their application in knowledge-intensive tasks. Retriever-augmented generation (RAG) offers a solution, but the non-parametric nature of the retriever hinders its deep interaction with LLM. In this work, we propose to decouple memorization from the LLM decoder using a pretrained, differentiable external memory. The external memory is an MLP pretrained by imitating the behavior of a retriever on the entire pretraining dataset. Our resulting architecture, which comprises a transformer decoder and an external MLP memory pretrained on language modeling and retriever imitation respectively, demonstrates strong perplexity and performance on downstream tasks. Experiments show our architecture exhibits steeper power-law scaling with model size, achieving 17.5% and 24.1% improvement on WikiText-103 and Web datasets compared to decoder-only models while benefiting from added training without overfitting. We demonstrate superior performance on three hallucination benchmarks and nine memory-intensive tasks. Additionally, our approach delivers $80\times$ speedup over $k$NN-LM (500M tokens) and $1.3\times$ faster inference than decoder-only models. Unlike $k$NN-LM, which impairs reasoning, our MLP memory improves StrategyQA performance. We will open-source our code and models in the future.

[Arxiv](https://arxiv.org/abs/2508.01832)