# CoCoLex：基于信心的复制解码用于法律文本生成

发布时间：2025年08月07日

`LLM应用

摘要中讨论了大型语言模型在法律领域的应用，提出了一种新的解码策略（CoCoLex）来提高生成内容的保真度和上下文整合。虽然提到了RAG作为背景，但主要贡献在于改进LLM的应用，因此归类为LLM应用。` `文本生成`

> CoCoLex: Confidence-guided Copy-based Decoding for Grounded Legal Text Generation

# 摘要

> 大型语言模型（LLMs）因能处理长且复杂的上下文而在法律领域具有巨大潜力，但其生成不忠实、无根据或幻觉内容的倾向限制了其应用。检索增强生成虽然通过外部知识 grounding 提供了有效解决方案，却无法保证上下文的有效整合。为此，我们提出了上下文感知解码策略来放大相关上下文的影响，但这些方法通常未能显式强制忠实于上下文。本研究引入了基于置信度的复制解码策略（CoCoLex）用于法律文本生成。CoCoLex通过动态插值模型生成的词汇分布与基于上下文复制的分布，确保了更高的源保真度。实验结果表明，CoCoLex在五个法律基准上优于现有方法，尤其在长文本生成任务中表现卓越。

> Due to their ability to process long and complex contexts, LLMs can offer key benefits to the Legal domain, but their adoption has been hindered by their tendency to generate unfaithful, ungrounded, or hallucinatory outputs. While Retrieval-Augmented Generation offers a promising solution by grounding generations in external knowledge, it offers no guarantee that the provided context will be effectively integrated. To address this, context-aware decoding strategies have been proposed to amplify the influence of relevant context, but they usually do not explicitly enforce faithfulness to the context. In this work, we introduce Confidence-guided Copy-based Decoding for Legal Text Generation (CoCoLex)-a decoding strategy that dynamically interpolates the model produced vocabulary distribution with a distribution derived based on copying from the context. CoCoLex encourages direct copying based on the model's confidence, ensuring greater fidelity to the source. Experimental results on five legal benchmarks demonstrate that CoCoLex outperforms existing context-aware decoding methods, particularly in long-form generation tasks.

[Arxiv](https://arxiv.org/abs/2508.05534)