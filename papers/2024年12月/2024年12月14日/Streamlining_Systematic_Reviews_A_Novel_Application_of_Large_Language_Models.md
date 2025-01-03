# 系统综述的简化：大型语言模型的创新应用

发布时间：2024年12月14日

`LLM应用

理由：这篇论文描述了一个基于大型语言模型（LLMs）的系统，用于自动化系统综述（SRs）中的文献筛选过程。该系统通过提示工程和检索增强生成（RAG）技术来提高筛选的效率和准确性。虽然提到了RAG技术，但论文的核心是LLM在具体应用场景（文献筛选）中的使用，因此归类为LLM应用更为合适。` `文献筛选`

> Streamlining Systematic Reviews: A Novel Application of Large Language Models

# 摘要

> # 摘要
系统综述（SRs）在制定基于证据的指南中至关重要，但文献筛选的耗时性常常成为瓶颈。我们开发并评估了一个基于大型语言模型（LLMs）的内部系统，旨在自动化标题/摘要和全文筛选，填补了这一领域的空白。以一项关于维生素D与跌倒的SR（14,439篇文章）为例，该系统通过提示工程进行标题/摘要筛选，并采用检索增强生成（RAG）技术进行全文筛选。结果显示，该系统实现了99.5%的文章排除率（AER）、99.6%的特异性、0%的假阴性率（FNR）和100%的阴性预测值（NPV）。筛选后，仅需手动审查78篇文章，其中包括传统方法识别的全部20篇，手动筛选时间减少了95.5%。相比之下，商业工具Rayyan在标题/摘要筛选中，AER为72.1%，FNR为5%。降低Rayyan的纳入阈值虽将FNR降至0%，但增加了筛选时间。通过覆盖两个筛选阶段，基于LLM的系统显著优于Rayyan和传统方法，将总筛选时间缩短至25.5小时，同时保持了高准确性。这些结果表明，LLMs在SR工作流程中具有变革性潜力，特别是在全文筛选阶段，提供了一个高效、准确且可扩展的解决方案。

> Systematic reviews (SRs) are essential for evidence-based guidelines but are often limited by the time-consuming nature of literature screening. We propose and evaluate an in-house system based on Large Language Models (LLMs) for automating both title/abstract and full-text screening, addressing a critical gap in the literature. Using a completed SR on Vitamin D and falls (14,439 articles), the LLM-based system employed prompt engineering for title/abstract screening and Retrieval-Augmented Generation (RAG) for full-text screening. The system achieved an article exclusion rate (AER) of 99.5%, specificity of 99.6%, a false negative rate (FNR) of 0%, and a negative predictive value (NPV) of 100%. After screening, only 78 articles required manual review, including all 20 identified by traditional methods, reducing manual screening time by 95.5%. For comparison, Rayyan, a commercial tool for title/abstract screening, achieved an AER of 72.1% and FNR of 5% when including articles Rayyan considered as undecided or likely to include. Lowering Rayyan's inclusion thresholds improved FNR to 0% but increased screening time. By addressing both screening phases, the LLM-based system significantly outperformed Rayyan and traditional methods, reducing total screening time to 25.5 hours while maintaining high accuracy. These findings highlight the transformative potential of LLMs in SR workflows by offering a scalable, efficient, and accurate solution, particularly for the full-text screening phase, which has lacked automation tools.

[Arxiv](https://arxiv.org/abs/2412.15247)