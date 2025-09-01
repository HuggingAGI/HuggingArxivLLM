# 追踪金融决策中的位置偏差：来自Qwen2.5的机制性见解

发布时间：2025年08月25日

`LLM应用` `金融科技`

> Tracing Positional Bias in Financial Decision-Making: Mechanistic Insights from Qwen2.5

# 摘要

> 随着大型语言模型（LLMs）在金融领域的应用日益广泛，高风险决策正暴露于那些微妙却未被充分研究的位置偏差之下。现代模型架构的复杂性与不透明性进一步放大了这一风险。我们首次提出了一个统一框架与基准，它不仅能检测和量化二元金融决策中的位置偏差，还能在开源Qwen2.5-instruct模型（1.5B--14B）中精准定位偏差的机制根源。我们的实证分析基于一个全新的金融真实数据集，结果显示位置偏差具有普遍性、规模敏感性，且在精细的提示设计和投资场景下容易再次出现；近因效应与首因效应还揭示了高风险情境中的新脆弱性。借助透明的机制可解释性方法，我们绘制了偏差在模型中的产生与传播路径，从而提供了跨提示类型和模型规模的可操作、可推广见解。通过将特定领域审计与模型可解释性相结合，我们的研究为严格的偏差诊断和实际缓解提供了新的方法学标准，并为金融系统中LLMs的负责任、可信部署奠定了重要指导基础。

> The growing adoption of large language models (LLMs) in finance exposes high-stakes decision-making to subtle, underexamined positional biases. The complexity and opacity of modern model architectures compound this risk. We present the first unified framework and benchmark that not only detects and quantifies positional bias in binary financial decisions but also pinpoints its mechanistic origins within open-source Qwen2.5-instruct models (1.5B--14B). Our empirical analysis covers a novel, finance-authentic dataset revealing that positional bias is pervasive, scale-sensitive, and prone to resurfacing under nuanced prompt designs and investment scenarios, with recency and primacy effects revealing new vulnerabilities in risk-laden contexts. Through transparent mechanistic interpretability, we map how and where bias emerges and propagates within the models to deliver actionable, generalizable insights across prompt types and scales. By bridging domain-specific audit with model interpretability, our work provides a new methodological standard for both rigorous bias diagnosis and practical mitigation, establishing essential guidance for responsible and trustworthy deployment of LLMs in financial systems.

[Arxiv](https://arxiv.org/abs/2508.18427)