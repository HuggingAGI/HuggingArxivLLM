# 借助大型语言模型，实现节能感知的并行科学代码自动化重构

发布时间：2025年05月04日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：尽管大型语言模型（LLMs）在生成并行科学代码方面的应用日益广泛，但现有研究大多关注代码的功能正确性，往往忽略了性能和能源效率。本文提出了一种基于LLM的自动化重构框架——LASSI-EE，它能够为给定的并行代码生成适用于目标并行系统的节能并行代码。通过多阶段的迭代处理流程，LASSI-EE在NVIDIA A100 GPU上测试的20个HeCBench基准测试中，85%的案例实现了平均47%的能源消耗减少。我们的研究结果不仅展示了LLMs生成正确代码的能力，更凸显了其在节能编程中的潜力。此外，我们还分享了框架中的关键见解和局限性，为未来改进提供了宝贵的指导。
LLM应用` `高性能计算` `科学计算`

> Leveraging LLMs to Automate Energy-Aware Refactoring of Parallel Scientific Codes

# 摘要

> 尽管大型语言模型（LLMs）在生成并行科学代码方面的应用日益广泛，但现有研究大多关注代码的功能正确性，往往忽略了性能和能源效率。本文提出了一种基于LLM的自动化重构框架——LASSI-EE，它能够为给定的并行代码生成适用于目标并行系统的节能并行代码。通过多阶段的迭代处理流程，LASSI-EE在NVIDIA A100 GPU上测试的20个HeCBench基准测试中，85%的案例实现了平均47%的能源消耗减少。我们的研究结果不仅展示了LLMs生成正确代码的能力，更凸显了其在节能编程中的潜力。此外，我们还分享了框架中的关键见解和局限性，为未来改进提供了宝贵的指导。

> While large language models (LLMs) are increasingly used for generating parallel scientific code, most current efforts emphasize functional correctness, often overlooking performance and energy considerations. In this work, we propose LASSI-EE, an automated LLM-based refactoring framework that generates energy-efficient parallel code on a target parallel system for a given parallel code as input. Through a multi-stage, iterative pipeline process, LASSI-EE achieved an average energy reduction of 47% across 85% of the 20 HeCBench benchmarks tested on NVIDIA A100 GPUs. Our findings demonstrate the broader potential of LLMs, not only for generating correct code but also for enabling energy-aware programming. We also address key insights and limitations within the framework, offering valuable guidance for future improvements.

[Arxiv](https://arxiv.org/abs/2505.02184)