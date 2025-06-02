# 利用检索增强大型语言模型中的原子事实核查，提升医学问答的可靠性和可解释性

发布时间：2025年05月30日

`LLM应用` `人工智能`

> Improving Reliability and Explainability of Medical Question Answering through Atomic Fact Checking in Retrieval-Augmented LLMs

# 摘要

> 大型语言模型（LLMs）具备丰富的医学知识，但在临床应用和监管合规中容易出现幻觉和引用不准确的问题。现有方法如检索增强生成虽部分缓解了这些问题，但幻觉和低事实层面的可解释性问题依然存在。我们提出了一种创新的原子事实核查框架，专为提升医疗长文本问答中LLMs的可靠性和可解释性而设计。该框架将LLM生成的回答分解为独立的、可验证的原子事实单位，并逐一与权威的医学指南知识库进行比对。这种方法不仅能够精准修正错误，还能直接追踪到来源文献，显著提升了医疗问答的事实准确性和可解释性。通过医学专家的多读者评估和自动化开放问答基准测试，我们证实了该框架在事实准确性和可解释性方面均有显著提升。我们的框架实现了整体回答质量40%的提升和50%的幻觉检测率。通过将每个原子事实追溯到数据库中最相关的片段，我们为生成的回答提供了颗粒化、透明的解释，填补了当前医疗AI应用中的关键空白。这项研究为LLMs在临床应用中的可信度和可靠性奠定了重要基础，满足了临床应用的关键要求，增强了人们对AI辅助医疗的信心。

> Large language models (LLMs) exhibit extensive medical knowledge but are prone to hallucinations and inaccurate citations, which pose a challenge to their clinical adoption and regulatory compliance. Current methods, such as Retrieval Augmented Generation, partially address these issues by grounding answers in source documents, but hallucinations and low fact-level explainability persist. In this work, we introduce a novel atomic fact-checking framework designed to enhance the reliability and explainability of LLMs used in medical long-form question answering. This method decomposes LLM-generated responses into discrete, verifiable units called atomic facts, each of which is independently verified against an authoritative knowledge base of medical guidelines. This approach enables targeted correction of errors and direct tracing to source literature, thereby improving the factual accuracy and explainability of medical Q&A. Extensive evaluation using multi-reader assessments by medical experts and an automated open Q&A benchmark demonstrated significant improvements in factual accuracy and explainability. Our framework achieved up to a 40% overall answer improvement and a 50% hallucination detection rate. The ability to trace each atomic fact back to the most relevant chunks from the database provides a granular, transparent explanation of the generated responses, addressing a major gap in current medical AI applications. This work represents a crucial step towards more trustworthy and reliable clinical applications of LLMs, addressing key prerequisites for clinical application and fostering greater confidence in AI-assisted healthcare.

[Arxiv](https://arxiv.org/abs/2505.24830)