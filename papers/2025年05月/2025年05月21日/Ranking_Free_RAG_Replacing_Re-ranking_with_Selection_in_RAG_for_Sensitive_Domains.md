# Ranking Free RAG: 以选择机制替代重新排序，应对敏感领域的 RAG 挑战

发布时间：2025年05月21日

`RAG`

> Ranking Free RAG: Replacing Re-ranking with Selection in RAG for Sensitive Domains

# 摘要

> 传统检索增强生成（RAG）管道依赖基于相似度的检索和重排序，这些方法不仅依赖于top-k等启发式规则，还存在缺乏可解释性、可理解性以及对抗性内容鲁棒性的缺陷。为了解决这一问题，我们提出了一种创新方法METEORA，该方法通过基于理由的选取策略取代了RAG中的重排序过程。

METEORA采用两阶段运行机制。首先，一个通用的LLM通过直接偏好优化进行偏好微调，根据输入查询生成理由。这些理由随后指导证据块选取引擎，该引擎在三个阶段中进行相关块的选取：局部相关性配对、全局选取的自适应截止以及上下文扩展。这一过程彻底摆脱了对top-k启发式规则的依赖。

此外，METEORA还通过Verifier LLM进行一致性检查，利用生成的理由检测和过滤中毒或误导性内容，从而实现安全生成。该框架在选取和验证过程中一致使用理由，提供了清晰的可解释和可理解的证据流。

实验结果表明，METEORA在涵盖法律、金融和学术研究领域的六个数据集上，相较于最先进的重排序方法，不仅将生成准确性提升了33.34%，还实现了50%的块使用减少。在对抗性设置中，其F1分数从基于困惑度的最先进防御基线的0.10显著提升至0.44，充分展示了其在面对中毒攻击时的强韧性。

代码已开源，获取方式请访问：https://anonymous.4open.science/r/METEORA-DC46/README.md

> Traditional Retrieval-Augmented Generation (RAG) pipelines rely on similarity-based retrieval and re-ranking, which depend on heuristics such as top-k, and lack explainability, interpretability, and robustness against adversarial content. To address this gap, we propose a novel method METEORA that replaces re-ranking in RAG with a rationale-driven selection approach. METEORA operates in two stages. First, a general-purpose LLM is preference-tuned to generate rationales conditioned on the input query using direct preference optimization. These rationales guide the evidence chunk selection engine, which selects relevant chunks in three stages: pairing individual rationales with corresponding retrieved chunks for local relevance, global selection with elbow detection for adaptive cutoff, and context expansion via neighboring chunks. This process eliminates the need for top-k heuristics. The rationales are also used for consistency check using a Verifier LLM to detect and filter poisoned or misleading content for safe generation. The framework provides explainable and interpretable evidence flow by using rationales consistently across both selection and verification. Our evaluation across six datasets spanning legal, financial, and academic research domains shows that METEORA improves generation accuracy by 33.34% while using approximately 50% fewer chunks than state-of-the-art re-ranking methods. In adversarial settings, METEORA significantly improves the F1 score from 0.10 to 0.44 over the state-of-the-art perplexity-based defense baseline, demonstrating strong resilience to poisoning attacks. Code available at: https://anonymous.4open.science/r/METEORA-DC46/README.md

[Arxiv](https://arxiv.org/abs/2505.16014)