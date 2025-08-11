# 低资源环境下LLMs知识注入方法的比较研究

发布时间：2025年08月08日

`LLM应用

理由：这篇论文探讨了如何在有限数据下将少量非结构化信息注入大型语言模型（LLMs），并研究了与灾难性遗忘现象的关系。它讨论了不同的数据增强算法、多样化提示生成方法以及模型自动生成合成训练数据的能力，这些都是与LLM应用相关的具体方法和实验结果。因此，这篇论文属于LLM应用类别。` `数据科学`

> Comparing Knowledge Injection Methods for LLMs in a Low-Resource Regime

# 摘要

> 大型语言模型（LLMs）需要海量文本才能有效学习新知识。尽管持续预训练或检索增强生成（RAG）方法已取得成功，但仅用几千或几百万个token更新LLM仍具挑战。本研究探讨将少量非结构化信息注入LLMs的任务及其与灾难性遗忘现象的关系。我们采用近期新闻数据集（确保与模型预训练数据无重叠）通过问答对测试模型对所学信息的掌握情况。从持续预训练基准出发，我们尝试不同数据增强算法生成合成数据以提升知识获取能力。实验表明，仅在有限数据上继续预训练可带来小幅提升，而向模型暴露多样化文本变体则显著改善新事实的学习效果——尤其是通过多样化提示生成更大变异性方法。此外，我们揭示了小数据场景下的遗忘现象，阐明了学习新内容与保持现有能力之间的微妙平衡。我们还证实了基于RAG的知识注入方法的敏感性，其通常导致控制数据集上更大的性能下降，相比参数化方法。最后，我们证明模型可自行生成有效的合成训练数据，为实现自我改进的模型更新提供了一条路径。我们在实验中使用的所有代码和生成数据均公开可用，为研究有限数据下LLMs的知识注入提供了资源，访问地址为https://github.com/hugoabonizio/knowledge-injection-methods。


> Large language models (LLMs) often require vast amounts of text to effectively acquire new knowledge. While continuing pre-training on large corpora or employing retrieval-augmented generation (RAG) has proven successful, updating an LLM with only a few thousand or million tokens remains challenging. In this work, we investigate the task of injecting small, unstructured information into LLMs and its relation to the catastrophic forgetting phenomenon. We use a dataset of recent news -- ensuring no overlap with the model's pre-training data -- to evaluate the knowledge acquisition by probing the model with question-answer pairs related the learned information. Starting from a continued pre-training baseline, we explored different augmentation algorithms to generate synthetic data to improve the knowledge acquisition capabilities. Our experiments show that simply continuing pre-training on limited data yields modest improvements, whereas exposing the model to diverse textual variations significantly improves the learning of new facts -- particularly with methods that induce greater variability through diverse prompting. Furthermore, we shed light on the forgetting phenomenon in small-data regimes, illustrating the delicate balance between learning new content and retaining existing capabilities. We also confirm the sensitivity of RAG-based approaches for knowledge injection, which often lead to greater degradation on control datasets compared to parametric methods. Finally, we demonstrate that models can generate effective synthetic training data themselves, suggesting a pathway toward self-improving model updates. All code and generated data used in our experiments are publicly available, providing a resource for studying efficient knowledge injection in LLMs with limited data at https://github.com/hugoabonizio/knowledge-injection-methods.

[Arxiv](https://arxiv.org/abs/2508.06178)