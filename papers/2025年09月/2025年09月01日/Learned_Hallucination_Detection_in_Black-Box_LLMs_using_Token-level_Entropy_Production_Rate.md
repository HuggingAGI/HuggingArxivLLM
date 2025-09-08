# 基于学习的黑盒LLMs幻觉检测：利用token级熵产生率

发布时间：2025年09月01日

`LLM应用` `金融科技`

> Learned Hallucination Detection in Black-Box LLMs using Token-level Entropy Production Rate

# 摘要

> 大型语言模型（LLM）在问答（QA）任务中生成的幻觉内容严重影响其实际应用可靠性。本文提出一种稳健的单样本幻觉检测实用方法，专为数据获取受限场景设计——例如与黑盒LLM API交互时，这类API通常仅暴露每个token的少量顶部候选对数概率。该方法直接从非贪婪解码生成的这些可用对数概率中提取不确定性指标：首先推导出熵产生率（EPR）作为基线，再通过监督学习增强性能。学习模型仅利用单个生成序列中可访问的顶部token熵贡献特征，无需多次重复查询。在多类QA数据集和多个LLM上的评估显示，该估计器相比单独使用EPR大幅提升了幻觉检测效果。关键在于，仅借助通常少量可用的对数概率（如每个token前<10个候选）即可实现高性能，证实了其实际效率和对这类API受限部署的适用性。这项研究提供了一种易于部署的实用技术，能通过单次生成增强QA与检索增强生成（RAG）系统中LLM响应的可信度，并在金融领域的实际应用中进一步验证了其价值——该框架分析了工业数据集年度报告的查询响应。

> Hallucinations in Large Language Model (LLM) outputs for Question Answering (QA) tasks critically undermine their real-world reliability. This paper introduces an applied methodology for robust, one-shot hallucination detection, specifically designed for scenarios with limited data access, such as interacting with black-box LLM APIs that typically expose only a few top candidate log-probabilities per token. Our approach derives uncertainty indicators directly from these readily available log-probabilities generated during non-greedy decoding. We first derive an Entropy Production Rate (EPR) metric that offers baseline performance, later augmented with supervised learning. Our learned model uses features representing the entropic contributions of the accessible top-ranked tokens within a single generated sequence, requiring no multiple query re-runs. Evaluated across diverse QA datasets and multiple LLMs, this estimator significantly improves hallucination detection over using EPR alone. Crucially, high performance is demonstrated using only the typically small set of available log-probabilities (e.g., top <10 per token), confirming its practical efficiency and suitability for these API-constrained deployments. This work provides a readily deployable technique to enhance the trustworthiness of LLM responses from a single generation pass in QA and Retrieval-Augmented Generation (RAG) systems, with its utility further demonstrated in a finance framework analyzing responses to queries on annual reports from an industrial dataset.

[Arxiv](https://arxiv.org/abs/2509.04492)