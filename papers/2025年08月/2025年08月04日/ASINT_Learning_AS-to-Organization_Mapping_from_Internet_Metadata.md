# ASINT：基于互联网元数据学习自治系统与组织的映射关系

发布时间：2025年08月04日

`LLM应用

解释：这篇论文主要讨论了ASINT，一个利用RAG和LLM进行更精准的组织归属分析的解决方案，重点在于应用LLM在实际任务中的效果，因此归类为LLM应用。` `互联网测量` `网络安全`

> ASINT: Learning AS-to-Organization Mapping from Internet Metadata

# 摘要

> 准确地将自治系统 (ASNs) 映射到其所有或运营的组织，是互联网测量研究和安全应用的基础。然而，现有方法往往仅依赖 WHOIS 或 PeeringDB，不仅遗漏了重要关系（如跨区域别名、上下级所有权），也无法整合分散在不同 RIR 标识符中的组织信息。为此，我们推出 ASINT，一个端到端的解决方案，通过融合批量注册数据和非结构化网络资源，并借助检索增强生成 (RAG) 引导大型语言模型 (LLM) 推理，实现更精准的组织归属分析。ASINT 通过多阶段流程，将 111,470 个 ASN 映射到 81,233 个组织家族，揭示了简单启发式难以捕捉的微妙关联。与 AS2ORG+ 和 AS-Sibling 相比，ASINT 识别出更多其他数据集忽视的跨区域分组（如运营商别名、品牌重塑）。此外，ASINT 的改进映射显著提升了安全和测量任务的性能：它揭示了多 27.5% 的内部组织 RPKI 错配，将误报劫持警报减少了 9.4%，并将错误 IP 租赁推断降低了 5.9%。最后，ASINT 支持定期更新和成本敏感的 LLM 选择，证明了利用更广泛的网络证据，可以构建一个更精准、动态演进的互联网组织架构视图。

> Accurately mapping Autonomous Systems (ASNs) to their owning or operating organizations underpins Internet measurement research and security applications. Yet existing approaches commonly rely solely on WHOIS or PeeringDB, missing important relationships (e.g., cross-regional aliases, parent-child ownership) and failing to unify organizations scattered across different RIR identifiers. We introduce ASINT, an end-to-end pipeline that fuses bulk registry data with unstructured Web sources, then employs retrieval-augmented generation (RAG) to guide large language model (LLM) inference. Through a multi-stage procedure, ASINT merges ASNs into "organization families," capturing nuanced ties beyond the scope of simpler heuristics.
  ASINT maps 111,470 ASNs to 81,233 organization families; compared to both AS2ORG+ and AS-Sibling, ASINT identifies more cross-regional groupings (e.g., operator aliases, rebrands) that other datasets overlook. Moreover, our refined mappings enhance multiple security and measurement tasks: ASINT exposes 27.5% more intra-organizational RPKI misconfigurations, cuts false-positive hijack alarms by 9.4%, and lowers erroneous IP leasing inferences by 5.9%.
  Finally, ASINT supports periodic updates and cost-sensitive LLM selection, demonstrating that broader Web evidence can provide a more accurate, evolving view of the Internet's organizational structure.

[Arxiv](https://arxiv.org/abs/2508.02571)