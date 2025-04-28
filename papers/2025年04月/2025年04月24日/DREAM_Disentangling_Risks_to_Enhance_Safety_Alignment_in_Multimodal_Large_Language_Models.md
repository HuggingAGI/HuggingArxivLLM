# # DREAM：解构风险，提升多模态大语言模型的安全对齐

发布时间：2025年04月24日

`LLM应用` `人工智能`

> DREAM: Disentangling Risks to Enhance Safety Alignment in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）因其整合了视觉与文本数据，带来了独特的安全挑战，由此引入了新的潜在攻击维度和复杂的风险组合。我们从深入分析入手，通过逐步推理解析多模态输入中的风险。研究发现，系统性的多模态风险解析显著提升了MLLMs的风险意识。借助多模态风险解析的强判别能力，我们提出了	extbf{DREAM}（	extit{	extbf{D}isentangling 	extbf{R}isks to 	extbf{E}nhance Safety 	extbf{A}lignment in 	extbf{M}LLMs}），这是一种通过监督微调和迭代式从AI反馈中进行强化学习（RLAIF）来提升MLLMs安全对齐的新方法。实验结果表明，DREAM在推理和训练阶段均显著提升了模型的安全性，同时保持了正常任务的性能（即避免过度安全化），其在SIUO安全且有效评分上相较于GPT-4V提升了16.17\%。数据和代码可访问https://github.com/Kizna1ver/DREAM。

> Multimodal Large Language Models (MLLMs) pose unique safety challenges due to their integration of visual and textual data, thereby introducing new dimensions of potential attacks and complex risk combinations. In this paper, we begin with a detailed analysis aimed at disentangling risks through step-by-step reasoning within multimodal inputs. We find that systematic multimodal risk disentanglement substantially enhances the risk awareness of MLLMs. Via leveraging the strong discriminative abilities of multimodal risk disentanglement, we further introduce \textbf{DREAM} (\textit{\textbf{D}isentangling \textbf{R}isks to \textbf{E}nhance Safety \textbf{A}lignment in \textbf{M}LLMs}), a novel approach that enhances safety alignment in MLLMs through supervised fine-tuning and iterative Reinforcement Learning from AI Feedback (RLAIF). Experimental results show that DREAM significantly boosts safety during both inference and training phases without compromising performance on normal tasks (namely oversafety), achieving a 16.17\% improvement in the SIUO safe\&effective score compared to GPT-4V. The data and code are available at https://github.com/Kizna1ver/DREAM.

[Arxiv](https://arxiv.org/abs/2504.18053)