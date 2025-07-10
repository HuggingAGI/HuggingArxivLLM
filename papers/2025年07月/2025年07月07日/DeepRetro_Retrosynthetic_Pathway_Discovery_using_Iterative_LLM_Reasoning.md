# # DeepRetro：基于迭代式LLM推理的逆合成路径发现

发布时间：2025年07月07日

`LLM应用

摘要中的论文详细描述了如何将大型语言模型（LLM）应用于逆合成问题，这是一个化学合成中的关键挑战。论文提出了一种名为DeepRetro的混合框架，结合了传统模板和LLM的能力，以发现新的合成路径。通过与传统方法的结合，该框架展示了LLM在复杂多步骤规划中的潜力，并在实际案例中成功应用。因此，这篇论文属于LLM应用类别，因为它展示了LLM在特定领域中的实际应用和解决方案。` `化学合成` `逆合成`

> DeepRetro: Retrosynthetic Pathway Discovery using Iterative LLM Reasoning

# 摘要

> 逆合成是合成复杂分子的核心技术，但在发现超越传统模板的新路径方面仍具挑战性。近期，基于大型语言模型（LLM）的逆合成方法展现出巨大潜力，但如何充分发挥LLM的推理能力以实现高效多步骤规划仍是亟待解决的问题。为此，我们开发了DeepRetro——一个开源、迭代、基于LLM的混合逆合成框架。该框架巧妙结合传统模板和蒙特卡洛树搜索工具的优势，与LLMs的生成能力形成互补，通过逐步反馈循环实现优化。首先，系统尝试使用模板引擎进行合成规划。如果失败，LLM将提出单步逆合成断开建议。这些建议需通过严格的合理性、稳定性和幻觉检查，随后将得到的前体分子递归反馈至流程中进行进一步评估。这种迭代优化机制实现了动态路径探索与修正。通过基准评估和案例研究，我们验证了该框架的潜力，展示了其识别可行且可能新颖的逆合成路径的能力。特别地，我们开发了一个交互式图形用户界面，使专业化学家能够提供“人工在环”反馈，进一步优化推理算法。这种方法成功为复杂天然产物生成了新颖的合成路径，证实了迭代LLM推理在推进复杂化学合成前沿方面的潜力。

> Retrosynthesis, the identification of precursor molecules for a target compound, is pivotal for synthesizing complex molecules, but faces challenges in discovering novel pathways beyond predefined templates. Recent large language model (LLM) approaches to retrosynthesis have shown promise but effectively harnessing LLM reasoning capabilities for effective multi-step planning remains an open question. To address this challenge, we introduce DeepRetro, an open-source, iterative, hybrid LLM-based retrosynthetic framework. Our approach integrates the strengths of conventional template-based/Monte Carlo tree search tools with the generative power of LLMs in a step-wise, feedback-driven loop. Initially, synthesis planning is attempted with a template-based engine. If this fails, the LLM subsequently proposes single-step retrosynthetic disconnections. Crucially, these suggestions undergo rigorous validity, stability, and hallucination checks before the resulting precursors are recursively fed back into the pipeline for further evaluation. This iterative refinement allows for dynamic pathway exploration and correction. We demonstrate the potential of this pipeline through benchmark evaluations and case studies, showcasing its ability to identify viable and potentially novel retrosynthetic routes. In particular, we develop an interactive graphical user interface that allows expert human chemists to provide human-in-the-loop feedback to the reasoning algorithm. This approach successfully generates novel pathways for complex natural product compounds, demonstrating the potential for iterative LLM reasoning to advance state-of-art in complex chemical syntheses.

[Arxiv](https://arxiv.org/abs/2507.07060)