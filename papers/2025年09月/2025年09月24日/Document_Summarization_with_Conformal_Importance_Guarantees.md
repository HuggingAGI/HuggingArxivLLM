# 基于共形重要性保证的文档摘要

发布时间：2025年09月24日

`LLM应用` `医疗健康` `法律科技`

> Document Summarization with Conformal Importance Guarantees

# 摘要

> 随着大型语言模型（LLMs）的兴起，自动摘要系统取得了飞速进展，但在医疗、法律、金融等高风险领域，其对关键内容的纳入仍缺乏可靠保障。为此，本研究提出了Conformal Importance Summarization——首个保重要性摘要生成框架，该框架通过共形预测实现了严格的、无分布依赖的覆盖保证。通过校准句子级重要性分数阈值，我们可生成抽取式文档摘要，且能满足用户对关键内容的覆盖度与召回率要求。该方法具有模型无关性，仅需少量校准数据，即可与现有黑盒LLM无缝衔接。在主流摘要基准数据集上的实验验证了，Conformal Importance Summarization能够达到理论保证的信息覆盖率。研究表明，将Conformal Importance Summarization与现有技术结合，可实现可靠可控的自动摘要，为AI摘要工具在关键场景中的安全部署奠定了基础。代码已开源，地址为https://github.com/layer6ai-labs/conformal-importance-summarization。

> Automatic summarization systems have advanced rapidly with large language models (LLMs), yet they still lack reliable guarantees on inclusion of critical content in high-stakes domains like healthcare, law, and finance. In this work, we introduce Conformal Importance Summarization, the first framework for importance-preserving summary generation which uses conformal prediction to provide rigorous, distribution-free coverage guarantees. By calibrating thresholds on sentence-level importance scores, we enable extractive document summarization with user-specified coverage and recall rates over critical content. Our method is model-agnostic, requires only a small calibration set, and seamlessly integrates with existing black-box LLMs. Experiments on established summarization benchmarks demonstrate that Conformal Importance Summarization achieves the theoretically assured information coverage rate. Our work suggests that Conformal Importance Summarization can be combined with existing techniques to achieve reliable, controllable automatic summarization, paving the way for safer deployment of AI summarization tools in critical applications. Code is available at https://github.com/layer6ai-labs/conformal-importance-summarization.

[Arxiv](https://arxiv.org/abs/2509.20461)