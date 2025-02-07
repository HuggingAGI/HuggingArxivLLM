# 基于基础设施即代码构件和大型语言模型的自动化微服务模式实例检测

发布时间：2025年02月06日

`LLM应用

**理由**：这篇论文主要讨论了利用大型语言模型（LLMs）来分析基础设施即代码（IaC）工件，以检测微服务模式实例。这属于LLM在实际应用中的使用，特别是用于软件架构分析和模式检测。因此，将其分类为“LLM应用”是合适的。` `软件工程` `微服务`

> Automated Microservice Pattern Instance Detection Using Infrastructure-as-Code Artifacts and Large Language Models

# 摘要

> # 摘要
尽管成本高昂，记录软件架构对于保存架构知识至关重要。微服务等架构模式实例提供了关键的软件结构信息，从业者应记录这些信息以防止知识流失。然而，架构模式可能无法通过源代码分析检测，需要借助其他类型的工件。此外，现有模式检测方法扩展性较差。本文介绍了我们正在进行的博士研究、早期实验以及名为MicroPAD的工具原型，该工具利用大型语言模型（LLMs）分析基础设施即代码（IaC）工件，旨在低成本、高效地检测微服务模式实例。早期实验在22个GitHub项目中运行了该原型三次，验证了83%的检测结果准确无误，且检测成本极低。这些结果表明该方法具有可行性，并通过降低自动化模式检测的门槛，有望让更多开发者受益于这类架构知识。最后，我们概述了研究方法、未来计划以及MicroPAD的潜在工业影响。

> Documenting software architecture is essential to preserve architecture knowledge, even though it is frequently costly. Architecture pattern instances, including microservice pattern instances, provide important structural software information. Practitioners should document this information to prevent knowledge vaporization. However, architecture patterns may not be detectable by analyzing source code artifacts, requiring the analysis of other types of artifacts. Moreover, many existing pattern detection instance approaches are complex to extend. This article presents our ongoing PhD research, early experiments, and a prototype for a tool we call MicroPAD for automating the detection of microservice pattern instances. The prototype uses Large Language Models (LLMs) to analyze Infrastructure-as-Code (IaC) artifacts to aid detection, aiming to keep costs low and maximize the scope of detectable patterns. Early experiments ran the prototype thrice in 22 GitHub projects. We verified that 83\% of the patterns that the prototype identified were in the project. The costs of detecting the pattern instances were minimal. These results indicate that the approach is likely viable and, by lowering the entry barrier to automating pattern instance detection, could help democratize developer access to this category of architecture knowledge. Finally, we present our overall research methodology, planned future work, and an overview of MicroPAD's potential industrial impact.

[Arxiv](https://arxiv.org/abs/2502.04188)