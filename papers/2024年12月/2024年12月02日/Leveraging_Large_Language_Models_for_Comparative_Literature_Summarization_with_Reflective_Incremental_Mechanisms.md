# 借助大型语言模型，运用反思增量机制来进行比较文学的总结

发布时间：2024年12月02日

`LLM应用` `学术研究` `文献综述`

> Leveraging Large Language Models for Comparative Literature Summarization with Reflective Incremental Mechanisms

# 摘要

> 在本文中，我们推出了 ChatCite 这一创新方法，它借助大型语言模型（LLMs）来生成比较文献摘要。在学术研究中，能够围绕研究之间的关键比较来总结研究论文是一项关键任务。现有的摘要模型虽能生成简洁的摘要，却难以提供深入的比较见解。ChatCite 引入了多步推理机制来克服这一局限，它能从论文中提取关键要素，逐步构建比较摘要，并通过反思性记忆过程优化输出。我们在自定义的 CompLit-LongContext 数据集（包含 1000 篇带有标注比较摘要的研究论文）上对 ChatCite 进行了评估。实验结果显示，在诸如 ROUGE 和新提出的 G-Score 等各种自动评估指标方面，ChatCite 优于包括 GPT-4、BART、T5 和 CoT 在内的若干基线方法。人工评估也进一步证实，与这些基线模型相比，ChatCite 生成的摘要更具连贯性、更有深度且更流畅。我们的方法在自动文献综述生成领域取得了显著进步，为研究人员提供了一个用于高效比较和综合科学研究的有力工具。

> In this paper, we introduce ChatCite, a novel method leveraging large language models (LLMs) for generating comparative literature summaries. The ability to summarize research papers with a focus on key comparisons between studies is an essential task in academic research. Existing summarization models, while effective at generating concise summaries, fail to provide deep comparative insights. ChatCite addresses this limitation by incorporating a multi-step reasoning mechanism that extracts critical elements from papers, incrementally builds a comparative summary, and refines the output through a reflective memory process. We evaluate ChatCite on a custom dataset, CompLit-LongContext, consisting of 1000 research papers with annotated comparative summaries. Experimental results show that ChatCite outperforms several baseline methods, including GPT-4, BART, T5, and CoT, across various automatic evaluation metrics such as ROUGE and the newly proposed G-Score. Human evaluation further confirms that ChatCite generates more coherent, insightful, and fluent summaries compared to these baseline models. Our method provides a significant advancement in automatic literature review generation, offering researchers a powerful tool for efficiently comparing and synthesizing scientific research.

[Arxiv](https://arxiv.org/abs/2412.02149)