# 通过潜在多面体量化MCP中的对话偏离研究

发布时间：2025年08月08日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：模型上下文协议（MCP）通过整合外部工具增强了大型语言模型（LLMs），实现了实时数据的动态聚合，从而提升任务执行效率。然而，其非隔离的执行环境带来了显著的安全与隐私风险。特别是，精心构造的对抗性内容可能引发工具投毒或间接提示注入，导致对话劫持、虚假信息传播或数据外泄等问题。现有的防御措施，如基于规则的过滤器或LLM驱动的检测方法，仍存在诸多局限，主要体现在依赖静态特征、计算效率低下，以及无法量化对话劫持的影响。为解决这些问题，我们提出了SecMCP，一个能够检测并量化对话偏离的安全框架。通过分析对抗性外部知识引起的潜在空间轨迹偏差，SecMCP在潜在多面体空间中建模LLM激活向量，识别对话动态中的异常偏移，从而实现对劫持、误导及数据外泄行为的主动探测。我们在三款先进的LLMs（Llama3、Vicuna、Mistral）上进行了测试，覆盖MS MARCO、HotpotQA、FinQA等基准数据集，结果表明SecMCP的AUROC评分超过0.915，同时保持了系统的可用性。我们的贡献包括：对MCP安全威胁的系统性分类、基于潜在多面体的对话偏离量化新方法，以及SecMCP有效性的实证验证。
LLM应用` `信息安全` `网络安全`

> Quantifying Conversation Drift in MCP via Latent Polytope

# 摘要

> 模型上下文协议（MCP）通过整合外部工具增强了大型语言模型（LLMs），实现了实时数据的动态聚合，从而提升任务执行效率。然而，其非隔离的执行环境带来了显著的安全与隐私风险。特别是，精心构造的对抗性内容可能引发工具投毒或间接提示注入，导致对话劫持、虚假信息传播或数据外泄等问题。现有的防御措施，如基于规则的过滤器或LLM驱动的检测方法，仍存在诸多局限，主要体现在依赖静态特征、计算效率低下，以及无法量化对话劫持的影响。为解决这些问题，我们提出了SecMCP，一个能够检测并量化对话偏离的安全框架。通过分析对抗性外部知识引起的潜在空间轨迹偏差，SecMCP在潜在多面体空间中建模LLM激活向量，识别对话动态中的异常偏移，从而实现对劫持、误导及数据外泄行为的主动探测。我们在三款先进的LLMs（Llama3、Vicuna、Mistral）上进行了测试，覆盖MS MARCO、HotpotQA、FinQA等基准数据集，结果表明SecMCP的AUROC评分超过0.915，同时保持了系统的可用性。我们的贡献包括：对MCP安全威胁的系统性分类、基于潜在多面体的对话偏离量化新方法，以及SecMCP有效性的实证验证。

> The Model Context Protocol (MCP) enhances large language models (LLMs) by integrating external tools, enabling dynamic aggregation of real-time data to improve task execution. However, its non-isolated execution context introduces critical security and privacy risks. In particular, adversarially crafted content can induce tool poisoning or indirect prompt injection, leading to conversation hijacking, misinformation propagation, or data exfiltration. Existing defenses, such as rule-based filters or LLM-driven detection, remain inadequate due to their reliance on static signatures, computational inefficiency, and inability to quantify conversational hijacking. To address these limitations, we propose SecMCP, a secure framework that detects and quantifies conversation drift, deviations in latent space trajectories induced by adversarial external knowledge. By modeling LLM activation vectors within a latent polytope space, SecMCP identifies anomalous shifts in conversational dynamics, enabling proactive detection of hijacking, misleading, and data exfiltration. We evaluate SecMCP on three state-of-the-art LLMs (Llama3, Vicuna, Mistral) across benchmark datasets (MS MARCO, HotpotQA, FinQA), demonstrating robust detection with AUROC scores exceeding 0.915 while maintaining system usability. Our contributions include a systematic categorization of MCP security threats, a novel latent polytope-based methodology for quantifying conversation drift, and empirical validation of SecMCP's efficacy.

[Arxiv](https://arxiv.org/abs/2508.06418)