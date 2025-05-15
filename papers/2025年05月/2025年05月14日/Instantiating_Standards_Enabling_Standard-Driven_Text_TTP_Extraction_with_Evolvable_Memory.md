# 基于标准的实例化：借助可演进内存实现标准驱动的文本 TTP 提取

发布时间：2025年05月14日

`LLM应用` `网络安全` `威胁情报`

> Instantiating Standards: Enabling Standard-Driven Text TTP Extraction with Evolvable Memory

# 摘要

> 从自然语言威胁报告中提取 MITRE ATT&CK 战术、技术和程序（TTPs）至关重要，但这一任务极具挑战性。现有方法虽关注数据驱动方法的性能指标，却往往忽视了确保忠实遵循官方标准的机制，导致 TTP 分配的可靠性和一致性受损，进而引发组织间的情报孤岛和威胁评估矛盾。为解决这一问题，我们提出了一种创新框架，将抽象的标准定义转化为可操作且情境化的知识。我们的方法借助大型语言模型（LLM）实现知识的生成、更新与应用。通过从标注示例和官方定义中提取双层情境知识实例，该框架构建了一个可演化的记忆库。第一层专注于识别情境上下文（如“通过编码子域与 C2 进行通信”），第二层则捕捉区分相似技术的关键特征（如根据编码方法与协议使用的不同，区分 T1132“数据编码”与 T1071“应用层协议”）。这种结构化方法不仅为可解释的 TTP 分配提供了透明基础，还增强了人类监督，同时推动了其他 TTP 提取系统的标准化。实验表明，我们的框架（采用 Qwen2.5-32B）较 GPT-4o 提高了 11% 的技术 F1 分数。定性分析进一步证实，在真实世界威胁情报场景中，我们的方法在标准化、透明度和可解释性方面均表现优异。据我们所知，这是首个利用 LLM 生成、更新和应用新知识进行 TTP 提取的研究。


> Extracting MITRE ATT\&CK Tactics, Techniques, and Procedures (TTPs) from natural language threat reports is crucial yet challenging. Existing methods primarily focus on performance metrics using data-driven approaches, often neglecting mechanisms to ensure faithful adherence to the official standard. This deficiency compromises reliability and consistency of TTP assignments, creating intelligence silos and contradictory threat assessments across organizations. To address this, we introduce a novel framework that converts abstract standard definitions into actionable, contextualized knowledge. Our method utilizes Large Language Model (LLM) to generate, update, and apply this knowledge. This framework populates an evolvable memory with dual-layer situational knowledge instances derived from labeled examples and official definitions. The first layer identifies situational contexts (e.g., "Communication with C2 using encoded subdomains"), while the second layer captures distinctive features that differentiate similar techniques (e.g., distinguishing T1132 "Data Encoding" from T1071 "Application Layer Protocol" based on whether the focus is on encoding methods or protocol usage). This structured approach provides a transparent basis for explainable TTP assignments and enhanced human oversight, while also helping to standardize other TTP extraction systems. Experiments show our framework (using Qwen2.5-32B) boosts Technique F1 scores by 11\% over GPT-4o. Qualitative analysis confirms superior standardization, enhanced transparency, and improved explainability in real-world threat intelligence scenarios. To the best of our knowledge, this is the first work that uses the LLM to generate, update, and apply the a new knowledge for TTP extraction.

[Arxiv](https://arxiv.org/abs/2505.09261)