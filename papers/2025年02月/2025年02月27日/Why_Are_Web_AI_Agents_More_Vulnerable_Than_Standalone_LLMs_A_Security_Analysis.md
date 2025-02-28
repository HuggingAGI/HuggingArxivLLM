# # 网络AI代理为何比独立大型语言模型更易受攻击？安全分析视角

发布时间：2025年02月27日

`Agent` `人工智能`

> Why Are Web AI Agents More Vulnerable Than Standalone LLMs? A Security Analysis

# 摘要

> Web AI代理在处理复杂网络导航任务方面表现卓越，但最新研究揭示了一个令人担忧的现象：相较于独立的大型语言模型（LLMs），它们的脆弱性更高，尽管两者都基于相同的安全对齐模型。这种差异尤其值得关注，因为Web AI代理的灵活性使其可能面临更多对抗性用户输入。本研究旨在构建一个解决这一问题的框架，深入探讨导致Web AI代理脆弱性增加的原因。研究发现，这种差异源于Web AI代理与独立LLMs之间的多方面差异，以及复杂信号中的细微差别——这些往往被简单的成功率等评估指标忽视。为应对这些挑战，我们提出了一种基于组件的分析方法和更细致、系统化的评估框架。通过细致入微的研究，我们识别出三个关键因素，它们显著加剧了Web AI代理的脆弱性：(1) 用户目标的系统提示嵌入，(2) 多步骤动作生成，以及(3) 观察能力。研究结果凸显了在AI代理设计中提升安全性和鲁棒性的紧迫性，并为制定针对性的防御策略提供了切实可行的见解。

> Recent advancements in Web AI agents have demonstrated remarkable capabilities in addressing complex web navigation tasks. However, emerging research shows that these agents exhibit greater vulnerability compared to standalone Large Language Models (LLMs), despite both being built upon the same safety-aligned models. This discrepancy is particularly concerning given the greater flexibility of Web AI Agent compared to standalone LLMs, which may expose them to a wider range of adversarial user inputs. To build a scaffold that addresses these concerns, this study investigates the underlying factors that contribute to the increased vulnerability of Web AI agents. Notably, this disparity stems from the multifaceted differences between Web AI agents and standalone LLMs, as well as the complex signals - nuances that simple evaluation metrics, such as success rate, often fail to capture. To tackle these challenges, we propose a component-level analysis and a more granular, systematic evaluation framework. Through this fine-grained investigation, we identify three critical factors that amplify the vulnerability of Web AI agents; (1) embedding user goals into the system prompt, (2) multi-step action generation, and (3) observational capabilities. Our findings highlights the pressing need to enhance security and robustness in AI agent design and provide actionable insights for targeted defense strategies.

[Arxiv](https://arxiv.org/abs/2502.20383)