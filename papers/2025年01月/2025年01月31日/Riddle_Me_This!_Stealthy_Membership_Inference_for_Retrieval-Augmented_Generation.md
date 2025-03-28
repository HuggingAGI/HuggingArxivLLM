# # 谜题来了！检索增强生成的隐秘成员推理

发布时间：2025年01月31日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统中的安全问题，特别是针对RAG数据存储中的文档的成员推断技术。论文提出了一种名为“审讯攻击（IA）”的成员推断技术，专门针对RAG系统中的文档进行攻击。因此，这篇论文的核心内容与RAG系统相关，应归类为RAG。` `信息安全`

> Riddle Me This! Stealthy Membership Inference for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）让大型语言模型（LLMs）无需调整参数，就能借助外部知识库生成有据可依的响应。然而，这种不依赖权重调整的方式虽然避免了参数泄露，却带来了新的风险：推理攻击者可能利用模型上下文中的检索文档。现有的成员推断和数据提取方法通常依赖于越狱或精心设计的非自然查询，但这些手段很容易被RAG系统中的查询重写技术识破或拦截。本文提出了一种名为“审讯攻击（IA）”的成员推断技术，专门针对RAG数据存储中的文档。通过设计只有在目标文档存在时才能回答的自然文本查询，我们的方法仅需30个查询即可成功推断，且隐蔽性极强；简单检测器对现有方法生成的对抗性提示的识别频率比我们的攻击高出约76倍。实验表明，在各种RAG配置下，我们的方法在TPR@1%FPR指标上比现有攻击提升了2倍，而每次文档推断的成本不到0.02美元。

> Retrieval-Augmented Generation (RAG) enables Large Language Models (LLMs) to generate grounded responses by leveraging external knowledge databases without altering model parameters. Although the absence of weight tuning prevents leakage via model parameters, it introduces the risk of inference adversaries exploiting retrieved documents in the model's context. Existing methods for membership inference and data extraction often rely on jailbreaking or carefully crafted unnatural queries, which can be easily detected or thwarted with query rewriting techniques common in RAG systems. In this work, we present Interrogation Attack (IA), a membership inference technique targeting documents in the RAG datastore. By crafting natural-text queries that are answerable only with the target document's presence, our approach demonstrates successful inference with just 30 queries while remaining stealthy; straightforward detectors identify adversarial prompts from existing methods up to ~76x more frequently than those generated by our attack. We observe a 2x improvement in TPR@1%FPR over prior inference attacks across diverse RAG configurations, all while costing less than $0.02 per document inference.

[Arxiv](https://arxiv.org/abs/2502.00306)