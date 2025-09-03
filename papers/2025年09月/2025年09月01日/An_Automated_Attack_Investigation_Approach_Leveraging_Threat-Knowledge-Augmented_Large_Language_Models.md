# 基于威胁知识增强大型语言模型的自动化攻击调查方法

发布时间：2025年09月01日

`RAG` `基础理论`

> An Automated Attack Investigation Approach Leveraging Threat-Knowledge-Augmented Large Language Models

# 摘要

> 高级持续性威胁（APTs）是由资深攻击者发起的长期、隐蔽入侵，旨在攻陷高价值系统以窃取数据或破坏运营。从海量异构日志中重建完整攻击链是有效攻击调查的关键，但现有方法存在平台通用性欠佳、对不断演变的攻击战术泛化能力有限及无法生成分析师可用报告等问题。大型语言模型（LLMs）虽具备强大的语义理解与总结能力，但在该领域难以捕捉准确重建所需的长程跨日志依赖关系。
  为解决这些问题，我们提出一种LLM赋能的攻击调查框架，该框架配备了动态适配的杀伤链对齐威胁知识库。我们将攻击相关行为组织为带有语义标注的阶段感知知识单元，使LLM能够迭代检索相关情报、进行因果推理并逐步扩展调查上下文。此过程可重建多阶段攻击场景，并生成连贯且通俗易懂的调查报告。在涵盖Windows和Linux系统的单主机与多主机环境的15个攻击场景（超过430万条日志事件，7.2 GB数据）上的评估显示，该系统平均真阳性率（TPR）达97.1%、平均假阳性率（FPR）仅0.2%，显著优于最先进方法ATLAS（其平均TPR为79.2%、平均FPR为29.1%）。

> Advanced Persistent Threats (APTs) are prolonged, stealthy intrusions by skilled adversaries that compromise high-value systems to steal data or disrupt operations. Reconstructing complete attack chains from massive, heterogeneous logs is essential for effective attack investigation, yet existing methods suffer from poor platform generality, limited generalization to evolving tactics, and an inability to produce analyst-ready reports. Large Language Models (LLMs) offer strong semantic understanding and summarization capabilities, but in this domain they struggle to capture the long-range, cross-log dependencies critical for accurate reconstruction.
  To solve these problems, we present an LLM-empowered attack investigation framework augmented with a dynamically adaptable Kill-Chain-aligned threat knowledge base. We organizes attack-relevant behaviors into stage-aware knowledge units enriched with semantic annotations, enabling the LLM to iteratively retrieve relevant intelligence, perform causal reasoning, and progressively expand the investigation context. This process reconstructs multi-phase attack scenarios and generates coherent, human-readable investigation reports. Evaluated on 15 attack scenarios spanning single-host and multi-host environments across Windows and Linux (over 4.3M log events, 7.2 GB of data), the system achieves an average True Positive Rate (TPR) of 97.1% and an average False Positive Rate (FPR) of 0.2%, significantly outperforming the SOTA method ATLAS, which achieves an average TPR of 79.2% and an average FPR of 29.1%.

[Arxiv](https://arxiv.org/abs/2509.01271)