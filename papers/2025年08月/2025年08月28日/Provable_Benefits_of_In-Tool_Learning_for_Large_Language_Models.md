# 工具内学习在大型语言模型中的可证明优势

发布时间：2025年08月28日

`RAG` `基础理论`

> Provable Benefits of In-Tool Learning for Large Language Models

# 摘要

> 配备检索、记忆或外部API的工具增强型语言模型正在重塑人工智能，然而其理论优势尚未被充分挖掘。本文针对这一问题展开研究，证明在事实召回任务中，工具内学习（外部检索）相比权重内学习（记忆）更具优势。我们发现，模型仅通过权重所能记忆的事实数量，从根本上受限于其参数规模；相比之下，借助简单高效的电路构造，工具使用可实现无界的事实召回。这些结论在对照实验中得到验证：使用工具的模型表现始终优于依赖记忆的模型。我们进一步发现，对于预训练大型语言模型，教授工具使用方法和通用规则，比将事实微调至内存中更为高效。本研究为工具增强型工作流奠定了理论与实证基础，阐明其不仅具备实用性，更被证明具有更强的可扩展性。

> Tool-augmented language models, equipped with retrieval, memory, or external APIs, are reshaping AI, yet their theoretical advantages remain underexplored. In this paper, we address this question by demonstrating the benefits of in-tool learning (external retrieval) over in-weight learning (memorization) for factual recall. We show that the number of facts a model can memorize solely in its weights is fundamentally limited by its parameter count. In contrast, we prove that tool-use enables unbounded factual recall via a simple and efficient circuit construction. These results are validated in controlled experiments, where tool-using models consistently outperform memorizing ones. We further show that for pretrained large language models, teaching tool-use and general rules is more effective than finetuning facts into memory. Our work provides both a theoretical and empirical foundation, establishing why tool-augmented workflows are not just practical, but provably more scalable.

[Arxiv](https://arxiv.org/abs/2508.20755)