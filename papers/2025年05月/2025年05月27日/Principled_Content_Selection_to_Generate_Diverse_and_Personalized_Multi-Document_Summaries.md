# # 生成多样化和个性化的多文档摘要，基于原则化内容选择

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了大型语言模型在多文档摘要任务中的应用，并提出了一种基于原则的内容选择方法来改善模型的表现。论文的重点在于如何优化LLM在特定任务中的应用，而不是探讨模型的理论或架构。因此，它属于LLM应用类别。` `文本摘要` `个性化摘要`

> Principled Content Selection to Generate Diverse and Personalized Multi-Document Summaries

# 摘要

> 尽管大型语言模型（LLMs）在处理长上下文方面的能力日益增强，但近期研究表明，它们仍然存在“中间迷失”现象（Liu et al., 2024），即对提供的上下文不同部分的关注程度不均。这一现象限制了它们在多文档摘要任务中覆盖多样化来源材料的能力，正如DiverseSumm基准（Huang et al., 2024）所指出的。在本研究中，我们认为，基于原则的内容选择是一种简单有效的方法，能够提升该任务中的来源覆盖范围。与让LLM在单一步骤中完成摘要不同，我们将任务明确划分为三个步骤——（1）将文档集合简化为原子关键点，（2）利用行列式点过程（DPP）选择优先考虑多样化内容的关键点，以及（3）重写生成最终摘要。通过将提示步骤（用于提取和重写）与基于原则的技术（用于内容选择）相结合，我们在DiverseSumm基准上，针对各种LLMs，持续提升了来源覆盖范围。最后，我们还展示了，通过将与用户意图的相关性纳入DPP核函数，我们可以生成个性化摘要，既覆盖相关来源信息，又保持全面覆盖。

> While large language models (LLMs) are increasingly capable of handling longer contexts, recent work has demonstrated that they exhibit the "lost in the middle" phenomenon (Liu et al., 2024) of unevenly attending to different parts of the provided context. This hinders their ability to cover diverse source material in multi-document summarization, as noted in the DiverseSumm benchmark (Huang et al., 2024). In this work, we contend that principled content selection is a simple way to increase source coverage on this task. As opposed to prompting an LLM to perform the summarization in a single step, we explicitly divide the task into three steps -- (1) reducing document collections to atomic key points, (2) using determinantal point processes (DPP) to perform select key points that prioritize diverse content, and (3) rewriting to the final summary. By combining prompting steps, for extraction and rewriting, with principled techniques, for content selection, we consistently improve source coverage on the DiverseSumm benchmark across various LLMs. Finally, we also show that by incorporating relevance to a provided user intent into the DPP kernel, we can generate personalized summaries that cover relevant source information while retaining coverage.

[Arxiv](https://arxiv.org/abs/2505.21859)