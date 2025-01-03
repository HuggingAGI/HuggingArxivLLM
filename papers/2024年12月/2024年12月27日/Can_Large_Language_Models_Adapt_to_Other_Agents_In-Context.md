# 大型语言模型能否在上下文中与其他智能体无缝协作？

发布时间：2024年12月27日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的心智理论能力，特别是字面心智理论和功能性心智理论的区分及其在LLMs中的表现。论文的核心在于对LLMs的理论能力进行评估和分析，揭示了LLMs在适应新情况时的归纳偏见。这些内容属于对LLMs的理论研究和能力评估，因此归类为“LLM理论”。` `人工智能` `心理学`

> Can Large Language Models Adapt to Other Agents In-Context?

# 摘要

> 随着研究社区致力于打造更智能、更个性化的AI助手，以应对多样化的用户需求，评估大型语言模型（LLMs）的心智理论能力成为热点。最近的研究显示，LLM的心智理论能力接近人类水平，令人瞩目。然而，我们的论文提出质疑，认为过去的研究并未直接评估代理性能，可能导致误导性结论。我们区分了字面心智理论（预测他人行为的能力）和功能性心智理论（基于行为预测的理性反应适应代理）。研究发现，顶级开源LLMs在字面心智理论方面表现出色，但在功能性心智理论方面表现欠佳，即使面对极其简单的合作伙伴策略。我们的研究揭示了LLMs在适应新情况时归纳偏见的双重性：虽然短期内表现优异，但长期来看，这种偏见可能阻碍最优行为的实现。

> As the research community aims to build better AI assistants that are more dynamic and personalized to the diversity of humans that they interact with, there is increased interest in evaluating the theory of mind capabilities of large language models (LLMs). Indeed, several recent studies suggest that LLM theory of mind capabilities are quite impressive, approximating human-level performance. Our paper aims to rebuke this narrative and argues instead that past studies were not directly measuring agent performance, potentially leading to findings that are illusory in nature as a result. We draw a strong distinction between what we call literal theory of mind i.e. measuring the agent's ability to predict the behavior of others and functional theory of mind i.e. adapting to agents in-context based on a rational response to predictions of their behavior. We find that top performing open source LLMs may display strong capabilities in literal theory of mind, depending on how they are prompted, but seem to struggle with functional theory of mind -- even when partner policies are exceedingly simple. Our work serves to highlight the double sided nature of inductive bias in LLMs when adapting to new situations. While this bias can lead to strong performance over limited horizons, it often hinders convergence to optimal long-term behavior.

[Arxiv](https://arxiv.org/abs/2412.19726)