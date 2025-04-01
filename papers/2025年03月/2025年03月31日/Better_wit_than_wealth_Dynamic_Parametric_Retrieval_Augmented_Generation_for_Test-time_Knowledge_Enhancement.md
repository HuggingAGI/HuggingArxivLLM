# 智胜于财：用于测试时知识增强的动态参数检索增强生成

发布时间：2025年03月31日

`RAG` `问答系统`

> Better wit than wealth: Dynamic Parametric Retrieval Augmented Generation for Test-time Knowledge Enhancement

# 摘要

> 检索增强生成（RAG）通过从外部来源检索相关文档并将其纳入上下文，增强了大型语言模型（LLMs）。虽然它通过提供事实性文本提高了可靠性，但随着上下文长度的增长，推理成本大幅增加，并引入了具有挑战性的RAG幻觉问题，这主要归因于LLMs中缺乏相应的参数化知识。一个高效的解决方案是在测试时增强LLMs的知识。参数化RAG（PRAG）通过将文档嵌入到LLMs的参数中，以执行测试时的知识增强，通过离线训练有效降低了推理成本。然而，其高昂的训练和存储成本，以及有限的泛化能力，严重限制了其实际应用。为了解决这些挑战，我们提出了动态参数化RAG（DyPRAG），一个利用轻量级参数翻译模型高效地将文档转换为参数化知识的新框架。DyPRAG不仅降低了推理、训练和存储成本，还能够动态生成参数化知识，无缝增强LLMs的知识，并以即插即用的方式在测试时解决知识冲突。在多个数据集上的广泛实验验证了DyPRAG的有效性和泛化能力，提供了一种强大且实用的RAG范式，实现了卓越的知识融合，并在实际应用中缓解了RAG幻觉问题。我们的代码可在https://github.com/Trae1ounG/DyPRAG获取。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by retrieving relevant documents from external sources and incorporating them into the context. While it improves reliability by providing factual texts, it significantly increases inference costs as context length grows and introduces challenging issue of RAG hallucination, primarily caused by the lack of corresponding parametric knowledge in LLMs. An efficient solution is to enhance the knowledge of LLMs at test-time. Parametric RAG (PRAG) addresses this by embedding document into LLMs parameters to perform test-time knowledge enhancement, effectively reducing inference costs through offline training. However, its high training and storage costs, along with limited generalization ability, significantly restrict its practical adoption. To address these challenges, we propose Dynamic Parametric RAG (DyPRAG), a novel framework that leverages a lightweight parameter translator model to efficiently convert documents into parametric knowledge. DyPRAG not only reduces inference, training, and storage costs but also dynamically generates parametric knowledge, seamlessly enhancing the knowledge of LLMs and resolving knowledge conflicts in a plug-and-play manner at test-time. Extensive experiments on multiple datasets demonstrate the effectiveness and generalization capabilities of DyPRAG, offering a powerful and practical RAG paradigm which enables superior knowledge fusion and mitigates RAG hallucination in real-world applications. Our code is available at https://github.com/Trae1ounG/DyPRAG.

[Arxiv](https://arxiv.org/abs/2503.23895)