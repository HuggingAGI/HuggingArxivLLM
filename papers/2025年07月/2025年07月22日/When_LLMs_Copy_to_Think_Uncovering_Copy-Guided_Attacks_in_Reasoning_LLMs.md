# LLMs 复制思考时：揭示推理 LLMs 中的复制引导攻击

发布时间：2025年07月22日

`LLM应用` `软件工程` `网络安全`

> When LLMs Copy to Think: Uncovering Copy-Guided Attacks in Reasoning LLMs

# 摘要

> 大型语言模型（LLMs）在代码自动化分析中发挥着重要作用，支持漏洞检测和代码理解等任务。然而，其应用也引入了新的安全风险。本文提出了一种新型基于提示的攻击——Copy-Guided 攻击（CGA），利用具有推理能力的LLMs的固有复制倾向。通过在外部代码片段中注入精心设计的触发器，攻击者可诱导模型在推理过程中复制恶意内容。这种攻击导致两类漏洞：推理长度操控（模型生成异常简短或过长的推理轨迹）和推理结果操控（模型输出误导性或错误结论）。我们通过优化问题形式化了CGA，并提出了一种基于梯度的方法来合成有效触发器。在先进推理LLMs上的实证评估表明，CGA能够可靠地诱导代码分析任务中的无限循环、提前终止、错误拒绝和语义扭曲。尽管在特定场景下效果显著，但计算限制使CGA在多样化提示中的推广面临挑战，为未来研究提供了开放问题。我们的研究揭示了LLM驱动开发管道中的关键漏洞，呼吁在提示级别防御机制方面取得紧急进展。

> Large Language Models (LLMs) have become integral to automated code analysis, enabling tasks such as vulnerability detection and code comprehension. However, their integration introduces novel attack surfaces. In this paper, we identify and investigate a new class of prompt-based attacks, termed Copy-Guided Attacks (CGA), which exploit the inherent copying tendencies of reasoning-capable LLMs. By injecting carefully crafted triggers into external code snippets, adversaries can induce the model to replicate malicious content during inference. This behavior enables two classes of vulnerabilities: inference length manipulation, where the model generates abnormally short or excessively long reasoning traces; and inference result manipulation, where the model produces misleading or incorrect conclusions. We formalize CGA as an optimization problem and propose a gradient-based approach to synthesize effective triggers. Empirical evaluation on state-of-the-art reasoning LLMs shows that CGA reliably induces infinite loops, premature termination, false refusals, and semantic distortions in code analysis tasks. While highly effective in targeted settings, we observe challenges in generalizing CGA across diverse prompts due to computational constraints, posing an open question for future research. Our findings expose a critical yet underexplored vulnerability in LLM-powered development pipelines and call for urgent advances in prompt-level defense mechanisms.

[Arxiv](https://arxiv.org/abs/2507.16773)