# 大型语言模型中的幻觉现象：一份全面的分类指南

发布时间：2025年08月03日

`LLM理论` `人工智能`

> A comprehensive taxonomy of hallucinations in Large Language Models

# 摘要

> 大型语言模型（LLMs）彻底革新了自然语言处理领域，但它们生成看似合理却事实错误或虚构内容的倾向仍然是一个关键挑战。本报告提供了一个关于LLM幻觉的全面分类法，首先给出了正式定义，并提出了一个理论框架，认为这种幻觉在可计算的LLM中是不可避免的，无论其架构或训练方式如何。

报告探讨了核心区别，区分了内在幻觉（与输入上下文矛盾）和外在幻觉（与训练数据或现实不符），以及事实性（绝对正确性）和忠实性（遵循输入）。接着，报告详细描述了具体表现形式，包括事实错误、上下文和逻辑不一致、时间混乱、伦理违规，以及在代码生成和多模态应用等领域的任务特定幻觉。

报告分析了根本原因，将其归类为数据相关问题、模型相关因素和提示相关影响。此外，报告还研究了影响幻觉感知的认知和人为因素，调查了检测评估基准和指标，并概述了缓解策略的架构和系统方法。最后，报告介绍了用于监控LLM发布和性能的网络资源。

本报告强调了LLM幻觉的复杂多面性，并强调鉴于其理论上的必然性，未来工作必须专注于强大的检测、缓解以及在关键应用中负责任和可靠的部署所需的持续人工监督。

> Large language models (LLMs) have revolutionized natural language processing, yet their propensity for hallucination, generating plausible but factually incorrect or fabricated content, remains a critical challenge. This report provides a comprehensive taxonomy of LLM hallucinations, beginning with a formal definition and a theoretical framework that posits its inherent inevitability in computable LLMs, irrespective of architecture or training. It explores core distinctions, differentiating between intrinsic (contradicting input context) and extrinsic (inconsistent with training data or reality), as well as factuality (absolute correctness) and faithfulness (adherence to input). The report then details specific manifestations, including factual errors, contextual and logical inconsistencies, temporal disorientation, ethical violations, and task-specific hallucinations across domains like code generation and multimodal applications. It analyzes the underlying causes, categorizing them into data-related issues, model-related factors, and prompt-related influences. Furthermore, the report examines cognitive and human factors influencing hallucination perception, surveys evaluation benchmarks and metrics for detection, and outlines architectural and systemic mitigation strategies. Finally, it introduces web-based resources for monitoring LLM releases and performance. This report underscores the complex, multifaceted nature of LLM hallucinations and emphasizes that, given their theoretical inevitability, future efforts must focus on robust detection, mitigation, and continuous human oversight for responsible and reliable deployment in critical applications.

[Arxiv](https://arxiv.org/abs/2508.01781)