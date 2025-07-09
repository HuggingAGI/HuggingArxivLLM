# 推出Answered with Evidence框架——评估大型语言模型对生物医学问题的回答是否具有充分的证据支持

发布时间：2025年06月30日

`RAG` `生物医学` `问答系统`

> Introducing Answered with Evidence -- a framework for evaluating whether LLM responses to biomedical questions are founded in evidence

# 摘要

> 大型语言模型（LLMs）在生物医学问答中的广泛应用引发了对其回答准确性和证据支持的担忧。为解决这一问题，我们提出了“Answered with Evidence”框架，用于评估LLM生成的回答是否基于科学文献。我们通过一个比较分析流程，对数千个医生提交的问题进行了分析，该流程包括：（1）Alexandria（原名Atropos Evidence Library），一个基于新型观察性研究的检索增强生成（RAG）系统，以及（2）两个基于PubMed的检索增强系统（System和Perplexity）。我们发现，基于PubMed的系统为约44%的问题提供了有证据支持的回答，而新型证据来源则为约50%的问题提供了支持。综合来看，这些来源使超过70%的生物医学问题得到了可靠回答。随着LLMs在总结科学内容方面的能力不断增强，要实现其最大价值，需要能够准确检索已发表和自动生成证据的系统，或在实时生成此类证据。

> The growing use of large language models (LLMs) for biomedical question answering raises concerns about the accuracy and evidentiary support of their responses. To address this, we present Answered with Evidence, a framework for evaluating whether LLM-generated answers are grounded in scientific literature. We analyzed thousands of physician-submitted questions using a comparative pipeline that included: (1) Alexandria, fka the Atropos Evidence Library, a retrieval-augmented generation (RAG) system based on novel observational studies, and (2) two PubMed-based retrieval-augmented systems (System and Perplexity). We found that PubMed-based systems provided evidence-supported answers for approximately 44% of questions, while the novel evidence source did so for about 50%. Combined, these sources enabled reliable answers to over 70% of biomedical queries. As LLMs become increasingly capable of summarizing scientific content, maximizing their value will require systems that can accurately retrieve both published and custom-generated evidence or generate such evidence in real time.

[Arxiv](https://arxiv.org/abs/2507.02975)