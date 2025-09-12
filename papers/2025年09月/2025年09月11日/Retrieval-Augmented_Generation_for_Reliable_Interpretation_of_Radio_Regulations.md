# 检索增强生成：无线电法规的可靠解读

发布时间：2025年09月11日

`RAG` `法律科技`

> Retrieval-Augmented Generation for Reliable Interpretation of Radio Regulations

# 摘要

> 我们针对无线电法规这一法律敏感且高风险领域，开展问答研究。我们提出面向电信领域的检索增强生成（RAG）流程，并首次（据我们所知）构建了该领域的多项选择评估集——该数据集基于权威来源，通过自动化过滤与人工验证构建而成。为评估检索质量，我们定义了领域专属检索指标，基于该指标，我们的检索器准确率达97%左右。除检索环节外，我们的方法还能在所有测试模型中稳定提升生成准确率。值得注意的是，若直接插入文档而不进行结构化检索，GPT-4o的性能提升微乎其微（不足1%）；而采用我们的流程后，相对性能提升近12%。这些结果表明，精准的知识锚定不仅能提供简洁而稳健的基线，更为监管问答任务提供了高效的领域专属解决方案。相关代码、评估脚本及衍生的问答数据集已开源，地址为https://github.com/Zakaria010/Radio-RAG。

> We study question answering in the domain of radio regulations, a legally sensitive and high-stakes area. We propose a telecom-specific Retrieval-Augmented Generation (RAG) pipeline and introduce, to our knowledge, the first multiple-choice evaluation set for this domain, constructed from authoritative sources using automated filtering and human validation. To assess retrieval quality, we define a domain-specific retrieval metric, under which our retriever achieves approximately 97% accuracy. Beyond retrieval, our approach consistently improves generation accuracy across all tested models. In particular, while naively inserting documents without structured retrieval yields only marginal gains for GPT-4o (less than 1%), applying our pipeline results in nearly a 12% relative improvement. These findings demonstrate that carefully targeted grounding provides a simple yet strong baseline and an effective domain-specific solution for regulatory question answering. All code and evaluation scripts, along with our derived question-answer dataset, are available at https://github.com/Zakaria010/Radio-RAG.

[Arxiv](https://arxiv.org/abs/2509.09651)