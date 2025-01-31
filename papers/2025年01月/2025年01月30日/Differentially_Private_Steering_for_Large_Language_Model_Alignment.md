# 差分隐私引导：大型语言模型的对齐之道

发布时间：2025年01月30日

`LLM理论

理由：这篇论文主要讨论了如何通过激活编辑来引导大型语言模型（LLMs）朝向期望行为，并提出了在差分隐私（DP）保证下编辑LLM激活的算法（PSA）。研究内容涉及LLM的理论基础，特别是如何通过修改LLM的表示来实现对齐，并确保隐私保护。因此，这篇论文更适合归类为“LLM理论”。` `人工智能` `隐私保护`

> Differentially Private Steering for Large Language Model Alignment

# 摘要

> # 摘要
将大型语言模型（LLMs）与人类价值观对齐，并避免不良行为（如幻觉）变得越来越重要。最近，通过激活编辑引导LLMs朝向期望行为已成为在推理时减少有害生成的有效方法。激活编辑通过保留正面演示（如真实）的信息并最小化负面演示（如幻觉）的信息来修改LLM表示。当这些演示来自私有数据集时，对齐的LLM可能会泄露这些私有样本中的信息。在这项工作中，我们首次研究了使用私有数据集对齐LLM行为。我们提出了	extit{underline{P}rivate underline{S}teering for LLM underline{A}lignment (PSA)}算法，以在差分隐私（DP）保证下编辑LLM激活。我们在七个基准上进行了广泛实验，使用了不同大小（0.5B到7B）和模型家族（LlaMa、Qwen、Mistral和Gemma）的开源LLMs。结果表明，PSA在LLM对齐中实现了DP保证，且性能损失最小，包括对齐指标、文本生成质量和推理能力。我们还开发了首个成员推理攻击（MIA），用于评估和审计通过激活编辑进行LLM引导的实证隐私。该攻击专门针对激活编辑，仅依赖生成的文本。实验支持了理论保证，展示了	extit{PSA}算法相比现有非私有技术的改进。

> Aligning Large Language Models (LLMs) with human values and away from undesirable behaviors (such as hallucination) has become increasingly important. Recently, steering LLMs towards a desired behavior via activation editing has emerged as an effective method to mitigate harmful generations at inference-time. Activation editing modifies LLM representations by preserving information from positive demonstrations (e.g., truthful) and minimising information from negative demonstrations (e.g., hallucinations). When these demonstrations come from a private dataset, the aligned LLM may leak private information contained in those private samples. In this work, we present the first study of aligning LLM behavior with private datasets. Our work proposes the \textit{underline{P}rivate underline{S}teering for LLM underline{A}lignment (PSA)} algorithm to edit LLM activations with differential privacy (DP) guarantees. We conduct extensive experiments on seven different benchmarks with open-source LLMs of different sizes (0.5B to 7B) and model families (LlaMa, Qwen, Mistral and Gemma). Our results show that PSA achieves DP guarantees for LLM alignment with minimal loss in performance, including alignment metrics, open-ended text generation quality, and general-purpose reasoning. We also develop the first Membership Inference Attack (MIA) for evaluating and auditing the empirical privacy for the problem of LLM steering via activation editing. Our attack is tailored for activation editing and relies solely on the generated texts without their associated probabilities. Our experiments support the theoretical guarantees by showing improved guarantees for our \textit{PSA} algorithm compared to several existing non-private techniques.

[Arxiv](https://arxiv.org/abs/2501.18532)