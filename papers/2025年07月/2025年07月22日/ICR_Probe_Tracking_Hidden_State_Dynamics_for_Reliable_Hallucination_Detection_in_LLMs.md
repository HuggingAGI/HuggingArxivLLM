# ICR探针：追踪LLM隐藏状态动态，实现可靠幻觉检测

发布时间：2025年07月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）中的幻觉生成问题，并提出了新的方法和评分机制来改进幻觉检测。研究涉及模型内部隐藏状态的动态演变，属于对模型理论的深入分析和优化，因此归类为LLM理论。` `模型优化`

> ICR Probe: Tracking Hidden State Dynamics for Reliable Hallucination Detection in LLMs

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，但幻觉生成问题影响了其可靠性。现有基于隐藏状态的幻觉检测方法多关注静态孤立表征，忽视了跨层的动态演变，限制了检测效果。为解决这一问题，我们聚焦于隐藏状态的更新过程，提出了新的ICR分数（信息对残差流的贡献），量化模块对隐藏状态更新的贡献。实证研究表明，ICR分数在幻觉检测中表现出色且可靠。基于此，我们开发了ICR探针方法，捕捉隐藏状态的跨层演变特征。实验结果表明，ICR探针以更少的参数实现了更优的检测效果。通过消融研究和案例分析，我们深入理解了该方法的内在机制，进一步提升了其可解释性。

> Large language models (LLMs) excel at various natural language processing tasks, but their tendency to generate hallucinations undermines their reliability. Existing hallucination detection methods leveraging hidden states predominantly focus on static and isolated representations, overlooking their dynamic evolution across layers, which limits efficacy. To address this limitation, we shift the focus to the hidden state update process and introduce a novel metric, the ICR Score (Information Contribution to Residual Stream), which quantifies the contribution of modules to the hidden states' update. We empirically validate that the ICR Score is effective and reliable in distinguishing hallucinations. Building on these insights, we propose a hallucination detection method, the ICR Probe, which captures the cross-layer evolution of hidden states. Experimental results show that the ICR Probe achieves superior performance with significantly fewer parameters. Furthermore, ablation studies and case analyses offer deeper insights into the underlying mechanism of this method, improving its interpretability.

[Arxiv](https://arxiv.org/abs/2507.16488)