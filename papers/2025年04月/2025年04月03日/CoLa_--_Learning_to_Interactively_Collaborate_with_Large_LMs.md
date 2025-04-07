# 与大型语言模型实现高效互动协作：CoLa

发布时间：2025年04月03日

`LLM应用` `问答系统` `人工智能`

> CoLa -- Learning to Interactively Collaborate with Large LMs

# 摘要

> 大型语言模型 (LLMs) 凭借其在广泛语言任务中的卓越表现，为人类与 AI 协作解决问题带来了新的可能性。通过大规模应用其直觉和推理策略，LLMs 能够显著增强人类的能力。我们研究了是否可以通过从人类演示中泛化，模拟人类引导者，从而指导 AI 系统解决复杂语言问题。我们提出了一种名为 CoLa 的新型自我引导学习范式，用于训练自动化 $	extit{引导者}$，并在两个问答数据集、一个解谜任务和一个受限文本生成任务中进行了评估。实验结果表明，CoLa 在所有领域中均优于现有方法。值得注意的是，一个小型训练引导者在作为引导者时的表现甚至优于像 GPT-4 这样强大的模型。我们通过在问答数据集上进行人类研究，比较了人类与自动化引导者所采用的策略。研究结果显示，自动化引导者通过灵活适应推理者的技能并进行深入分析，其策略优于人类，且在引导方式上存在显著差异。

> LLMs' remarkable ability to tackle a wide range of language tasks opened new opportunities for collaborative human-AI problem solving. LLMs can amplify human capabilities by applying their intuitions and reasoning strategies at scale. We explore whether human guides can be simulated, by generalizing from human demonstrations of guiding an AI system to solve complex language problems. We introduce CoLa, a novel self-guided learning paradigm for training automated $\textit{guides}$ and evaluate it on two QA datasets, a puzzle-solving task, and a constrained text generation task. Our empirical results show that CoLa consistently outperforms competitive approaches across all domains. Moreover, a small-sized trained guide outperforms a strong model like GPT-4 when acting as a guide. We compare the strategies employed by humans and automated guides by conducting a human study on a QA dataset. We show that automated guides outperform humans by adapting their strategies to reasoners' capabilities and conduct qualitative analyses highlighting distinct differences in guiding strategies.

[Arxiv](https://arxiv.org/abs/2504.02965)