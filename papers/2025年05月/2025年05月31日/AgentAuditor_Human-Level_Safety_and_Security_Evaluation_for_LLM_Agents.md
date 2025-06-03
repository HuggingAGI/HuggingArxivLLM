# # AgentAuditor：LLM 代理的人类级安全与安全评估

发布时间：2025年05月31日

`LLM应用

摘要中提到的论文专注于基于LLM的代理技术的安全性和可靠性评估，提出了一种新的推理框架和基准测试。虽然提到了代理技术，但核心是LLM的应用和评估方法的改进，因此归类为LLM应用。` `人工智能安全` `人工智能评估`

> AgentAuditor: Human-Level Safety and Security Evaluation for LLM Agents

# 摘要

> 尽管基于LLM的代理技术飞速发展，但对其安全性和可靠性的评估仍然是一个重大挑战。现有的基于规则或基于LLM的评估器常常忽视代理在逐步行动中的潜在风险，未能捕捉微妙含义，无法预见小问题的累积效应，且容易被模糊的安全或安全规则所困扰。为应对这一评估危机，我们引入了\sys，这是一个通用的、无需训练的、带有记忆增强的推理框架，赋予LLM评估器模拟人类专家评估的能力。\sys通过让LLM自适应地提取结构化语义特征（如场景、风险、行为）并为过去交互生成相关的链式推理轨迹，构建了一个经验记忆库。随后，一个多阶段、上下文感知的检索增强生成过程动态检索最相关的推理经验，指导LLM评估器对新案例的评估。此外，我们开发了\data，这是首个旨在检查基于LLM的评估器能否有效识别安全风险和安全威胁的基准测试。\data包含	extbf{2293}个精心标注的交互记录，涵盖	extbf{29}个应用场景中的	extbf{15}种风险类型。其关键特色在于对模糊风险情境的细致处理，采用``严格''和``宽松''两种判断标准。实验表明，\sys不仅在所有基准测试中持续提升了LLM的评估性能，还为代理安全性和安全性设立了新的行业标准，达到了与人类相当的准确水平。我们的工作已公开发布，供社区参考和使用。

> Despite the rapid advancement of LLM-based agents, the reliable evaluation of their safety and security remains a significant challenge. Existing rule-based or LLM-based evaluators often miss dangers in agents' step-by-step actions, overlook subtle meanings, fail to see how small issues compound, and get confused by unclear safety or security rules. To overcome this evaluation crisis, we introduce \sys, a universal, training-free, memory-augmented reasoning framework that empowers LLM evaluators to emulate human expert evaluators. \sys constructs an experiential memory by having an LLM adaptively extract structured semantic features (e.g., scenario, risk, behavior) and generate associated chain-of-thought reasoning traces for past interactions. A multi-stage, context-aware retrieval-augmented generation process then dynamically retrieves the most relevant reasoning experiences to guide the LLM evaluator's assessment of new cases. Moreover, we developed \data, the first benchmark designed to check how well LLM-based evaluators can spot both safety risks and security threats. \data comprises \textbf{2293} meticulously annotated interaction records, covering \textbf{15} risk types across \textbf{29} application scenarios. A key feature of \data is its nuanced approach to ambiguous risk situations, employing ``Strict'' and ``Lenient'' judgment standards. Experiments demonstrate that \sys not only consistently improves the evaluation performance of LLMs across all benchmarks but also sets a new state-of-the-art in LLM-as-a-judge for agent safety and security, achieving human-level accuracy. Our work is openly openly accessible.

[Arxiv](https://arxiv.org/abs/2506.00641)