# 本文全面审视了大型语言模型中的幻觉缓解策略，旨在探索如何有效减少模型生成不真实或不恰当内容的风险。

发布时间：2024年01月08日

`LLM应用` `语言模型` `信息安全`

> A Comprehensive Survey of Hallucination Mitigation Techniques in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）日益精于模仿人类的写作风格，它们产生看似真实却无根据内容的倾向成为了一个主要难题。这种幻觉现象可能是将这些强大的模型安全地应用于现实世界、影响人们日常生活的系统的最大障碍。实现LLMs在实际应用中的广泛采纳，关键在于解决和减轻幻觉问题。与传统的AI系统不同，LLMs在训练过程中接触了大量的网络文本数据，这使它们能够展现出卓越的语言能力，但同时也可能使它们从训练数据的偏见中推断信息、误解模糊提示或调整信息以表面上与输入相符。在依赖语言生成技术处理敏感事务，如医疗记录摘要、财务分析报告等时，这一点尤为令人担忧。本文综合考察了超过32种旨在减轻LLMs幻觉问题的技术，其中包括检索增强生成（Lewis等人，2021年）、知识检索（Varshney等人，2023年）、CoNLI（Lei等人，2023年）和CoVe（Dhuliawala等人，2023年）。我们进一步提出了一个详细的分类体系，根据数据集使用、常规任务、反馈机制和检索器类型等不同参数对这些方法进行分类。这样的分类有助于明确各种专门针对LLMs幻觉问题的方法。同时，我们还分析了这些技术所固有的挑战和局限，为未来在LLMs领域内解决幻觉及其相关现象的研究奠定了坚实的基础。

> As Large Language Models (LLMs) continue to advance in their ability to write human-like text, a key challenge remains around their tendency to hallucinate generating content that appears factual but is ungrounded. This issue of hallucination is arguably the biggest hindrance to safely deploying these powerful LLMs into real-world production systems that impact people's lives. The journey toward widespread adoption of LLMs in practical settings heavily relies on addressing and mitigating hallucinations. Unlike traditional AI systems focused on limited tasks, LLMs have been exposed to vast amounts of online text data during training. While this allows them to display impressive language fluency, it also means they are capable of extrapolating information from the biases in training data, misinterpreting ambiguous prompts, or modifying the information to align superficially with the input. This becomes hugely alarming when we rely on language generation capabilities for sensitive applications, such as summarizing medical records, financial analysis reports, etc. This paper presents a comprehensive survey of over 32 techniques developed to mitigate hallucination in LLMs. Notable among these are Retrieval Augmented Generation (Lewis et al, 2021), Knowledge Retrieval (Varshney et al,2023), CoNLI (Lei et al, 2023), and CoVe (Dhuliawala et al, 2023). Furthermore, we introduce a detailed taxonomy categorizing these methods based on various parameters, such as dataset utilization, common tasks, feedback mechanisms, and retriever types. This classification helps distinguish the diverse approaches specifically designed to tackle hallucination issues in LLMs. Additionally, we analyze the challenges and limitations inherent in these techniques, providing a solid foundation for future research in addressing hallucinations and related phenomena within the realm of LLMs.

[Arxiv](https://arxiv.org/abs/2401.01313)