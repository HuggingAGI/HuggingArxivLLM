# # RuleGenie: SIEM检测规则集优化方案
RuleGenie: SIEM检测规则集优化方案

发布时间：2025年05月10日

`LLM应用` `SIEM`

> RuleGenie: SIEM Detection Rule Set Optimization

# 摘要

> SIEM系统作为安全信息与事件管理的核心，通过基于规则的逻辑来检测和应对威胁。然而，系统中冗余或重叠的规则会导致过多的误报，使分析师因告警疲劳而效率下降，同时也增加了实际威胁处理的计算开销和响应延迟。因此，优化SIEM规则集对于提升运营效率至关重要。尽管如此，该领域的研究仍显不足，现有实践主要依赖于耗时且易出错的手动优化方法，这主要源于企业级规则集的规模和复杂性。为填补这一空白，我们推出了RuleGenie——一个由大型语言模型（LLM）驱动的推荐系统，专为优化SIEM规则集而设计。我们的方法借助变压器模型的多头注意力机制生成SIEM规则嵌入，并通过相似性匹配算法识别最相关的规则。随后，LLM运用其信息提取、语言理解和推理能力，分析规则相似性、评估威胁覆盖范围及性能指标，并为完善规则集提供优化建议。通过自动化规则优化流程，RuleGenie不仅帮助安全团队聚焦于战略性任务，还提升了SIEM系统的整体效率，进而强化了组织的安全防护能力。我们在包括Splunk、Sigma和AQL（Ariel查询语言）在内的多种真实世界SIEM规则格式上对RuleGenie进行了全面评估，验证了其跨平台适应性和在各类安全架构中的灵活性。实验结果表明，RuleGenie能够有效识别冗余规则，显著降低误报率并提升整体规则效能。

> SIEM systems serve as a critical hub, employing rule-based logic to detect and respond to threats. Redundant or overlapping rules in SIEM systems lead to excessive false alerts, degrading analyst performance due to alert fatigue, and increase computational overhead and response latency for actual threats. As a result, optimizing SIEM rule sets is essential for efficient operations. Despite the importance of such optimization, research in this area is limited, with current practices relying on manual optimization methods that are both time-consuming and error-prone due to the scale and complexity of enterprise-level rule sets. To address this gap, we present RuleGenie, a novel large language model (LLM) aided recommender system designed to optimize SIEM rule sets. Our approach leverages transformer models' multi-head attention capabilities to generate SIEM rule embeddings, which are then analyzed using a similarity matching algorithm to identify the top-k most similar rules. The LLM then processes the rules identified, utilizing its information extraction, language understanding, and reasoning capabilities to analyze rule similarity, evaluate threat coverage and performance metrics, and deliver optimized recommendations for refining the rule set. By automating the rule optimization process, RuleGenie allows security teams to focus on more strategic tasks while enhancing the efficiency of SIEM systems and strengthening organizations' security posture. We evaluated RuleGenie on a comprehensive set of real-world SIEM rule formats, including Splunk, Sigma, and AQL (Ariel query language), demonstrating its platform-agnostic capabilities and adaptability across diverse security infrastructures. Our experimental results show that RuleGenie can effectively identify redundant rules, which in turn decreases false positive rates and enhances overall rule efficiency.

[Arxiv](https://arxiv.org/abs/2505.06701)