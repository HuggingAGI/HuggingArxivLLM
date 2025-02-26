# 通过采样推理探知视觉大语言模型的知识边界

发布时间：2025年02月25日

`RAG` `计算机视觉` `人工智能`

> Detecting Knowledge Boundary of Vision Large Language Models by Sampling-Based Inference

# 摘要

> 尽管视觉大语言模型（VLLMs）与文本大语言模型（LLMs）一样取得了进展，但它们在处理需要实时信息或知识密集型问题时仍存在局限性。盲目采用检索增强生成（RAG）技术虽然有效，但成本高昂。为了减少对检索的依赖，同时保持或提升性能优势，我们提出了一种检测VLLMs知识边界的方法，从而更高效地利用RAG等技术。具体来说，我们提出了一种具有两种变体的方法，通过在自动构建的数据集上对VLLM进行微调以实现边界识别。实验结果表明，我们的方法成功描绘了VLLM的知识边界，从而减少了盲目检索，同时保持或提升了性能。此外，我们发现为一个VLLM识别的知识边界可以作为其他VLLMs的替代边界。代码将在 https://github.com/Chord-Chen-30/VLLM-KnowledgeBoundary 发布。

> Despite the advancements made in Visual Large Language Models (VLLMs), like text Large Language Models (LLMs), they have limitations in addressing questions that require real-time information or are knowledge-intensive. Indiscriminately adopting Retrieval Augmented Generation (RAG) techniques is an effective yet expensive way to enable models to answer queries beyond their knowledge scopes. To mitigate the dependence on retrieval and simultaneously maintain, or even improve, the performance benefits provided by retrieval, we propose a method to detect the knowledge boundary of VLLMs, allowing for more efficient use of techniques like RAG. Specifically, we propose a method with two variants that fine-tunes a VLLM on an automatically constructed dataset for boundary identification. Experimental results on various types of Visual Question Answering datasets show that our method successfully depicts a VLLM's knowledge boundary based on which we are able to reduce indiscriminate retrieval while maintaining or improving the performance. In addition, we show that the knowledge boundary identified by our method for one VLLM can be used as a surrogate boundary for other VLLMs. Code will be released at https://github.com/Chord-Chen-30/VLLM-KnowledgeBoundary

[Arxiv](https://arxiv.org/abs/2502.18023)