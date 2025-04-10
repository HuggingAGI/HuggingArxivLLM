# 大型语言模型能否模拟逆向表现的虚拟角色？反事实指令遵循能力的基准测试

发布时间：2025年04月08日

`LLM应用` `虚拟环境`

> Can LLMs Simulate Personas with Reversed Performance? A Benchmark for Counterfactual Instruction Following

# 摘要

> 大型语言模型（LLMs）正被广泛用于虚拟环境中模拟角色，凭借其遵循指令的强大能力。然而，我们发现，即使是当前最先进的LLMs也无法模拟具备反向性能的角色（如教育场景中低熟练度的学生角色），这严重影响了模拟的多样性和实际应用价值。在本研究中，我们以数学推理为典型场景，首次提出了一个评估LLMs模拟反向性能角色能力的基准数据集，并将其命名为“反事实指令遵循”。我们对开源和闭源的LLMs进行了测试，发现包括OpenAI o1推理模型在内的所有模型在遵循反事实指令以模拟反向性能角色时均表现不佳。更值得注意的是，同时模拟角色的绩效水平和种族人口特征会进一步加剧这一问题。这些发现不仅揭示了反事实指令遵循的巨大挑战，也凸显了进一步研究的迫切需求。

> Large Language Models (LLMs) are now increasingly widely used to simulate personas in virtual environments, leveraging their instruction-following capability. However, we discovered that even state-of-the-art LLMs cannot simulate personas with reversed performance (e.g., student personas with low proficiency in educational settings), which impairs the simulation diversity and limits the practical applications of the simulated environments. In this work, using mathematical reasoning as a representative scenario, we propose the first benchmark dataset for evaluating LLMs on simulating personas with reversed performance, a capability that we dub "counterfactual instruction following". We evaluate both open-weight and closed-source LLMs on this task and find that LLMs, including the OpenAI o1 reasoning model, all struggle to follow counterfactual instructions for simulating reversedly performing personas. Intersectionally simulating both the performance level and the race population of a persona worsens the effect even further. These results highlight the challenges of counterfactual instruction following and the need for further research.

[Arxiv](https://arxiv.org/abs/2504.06460)