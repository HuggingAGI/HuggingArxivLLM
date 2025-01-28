# 参数化检索增强生成

发布时间：2025年01月27日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术的改进，提出了一种新的RAG范式——参数化检索增强生成（Parametric RAG）。论文的核心内容围绕如何通过文档参数化将外部知识直接集成到LLM的前馈网络（FFN）参数中，从而提升LLMs的知识增强效果和效率。因此，这篇论文应归类为RAG。` `知识增强`

> Parametric Retrieval Augmented Generation

# 摘要

> # 摘要
检索增强生成（RAG）技术通过解决幻觉、过时知识和领域适应等问题，显著提升了大型语言模型（LLMs）的可靠性。现有RAG方法通常将从外部语料库或数据库中检索到的相关文档附加到LLMs的输入中，以指导生成过程，我们称之为上下文知识注入。尽管这种方法简单有效，但它存在一些固有缺陷。首先，增加上下文长度和相关文档数量可能导致计算开销增加和性能下降，尤其是在复杂推理任务中。更重要的是，上下文知识注入主要在输入层面操作，而LLMs的内部知识则存储在参数中，这种不匹配限制了上下文方法的能力。为此，我们提出了参数化检索增强生成（Parametric RAG），这是一种新的RAG范式，通过文档参数化将外部知识直接集成到LLM的前馈网络（FFN）参数中。这种方法不仅节省了在线计算成本，还更深入地将外部知识融入LLM的参数化知识空间。实验表明，Parametric RAG显著提升了LLMs知识增强的效果和效率，并且可以与上下文RAG方法结合，进一步提升性能。
我们已在以下匿名GitHub链接中开源了所有代码、数据和模型：https://github.com/oneal2000/PRAG

> Retrieval-augmented generation (RAG) techniques have emerged as a promising solution to enhance the reliability of large language models (LLMs) by addressing issues like hallucinations, outdated knowledge, and domain adaptation. In particular, existing RAG methods append relevant documents retrieved from external corpus or databases to the input of LLMs to guide their generation process, which we refer to as the in-context knowledge injection method. While this approach is simple and often effective, it has inherent limitations. Firstly, increasing the context length and number of relevant documents can lead to higher computational overhead and degraded performance, especially in complex reasoning tasks. More importantly, in-context knowledge injection operates primarily at the input level, but LLMs store their internal knowledge in their parameters. This gap fundamentally limits the capacity of in-context methods. To this end, we introduce Parametric retrieval-augmented generation (Parametric RAG), a new RAG paradigm that integrates external knowledge directly into the parameters of feed-forward networks (FFN) of an LLM through document parameterization. This approach not only saves online computational costs by eliminating the need to inject multiple documents into the LLMs' input context, but also deepens the integration of external knowledge into the parametric knowledge space of the LLM. Experimental results demonstrate that Parametric RAG substantially enhances both the effectiveness and efficiency of knowledge augmentation in LLMs. Also, it can be combined with in-context RAG methods to achieve even better performance.
  We have open-sourced all the code, data, and models in the following anonymized GitHub link: https://github.com/oneal2000/PRAG

[Arxiv](https://arxiv.org/abs/2501.15915)