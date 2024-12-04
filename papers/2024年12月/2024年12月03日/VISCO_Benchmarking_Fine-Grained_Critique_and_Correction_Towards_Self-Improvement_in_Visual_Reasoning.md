# VISCO：针对视觉推理中自我改进的细粒度批评与纠正的基准测试

发布时间：2024年12月03日

`LLM应用` `视觉语言模型` `人工智能`

> VISCO: Benchmarking Fine-Grained Critique and Correction Towards Self-Improvement in Visual Reasoning

# 摘要

> 大型视觉语言模型（LVLMs）批判和修正自身推理的能力，是其实现自我提升的关键要素。然而，对于 LVLMs 此类能力的系统性分析仍有所缺失。我们推出了 VISCO，这是首个全面剖析 LVLMs 精细批判与修正能力的基准。相较于现有通过单个标量值来评判整个推理过程的工作[4]，VISCO 具备密集且精细的批判特性，要求 LVLMs 评估思维链中每一步的正确性，并给出自然语言解释来支撑其判断。对 24 个 LVLMs 的广泛评估显示，人工撰写的批判显著提升了修正后的性能，展现出自我改进策略的潜力。但模型生成的批判帮助不大，有时甚至对性能有负面影响，这表明批判环节是关键瓶颈。我们找出了批判失败的三种常见模式：无法批判视觉感知、不愿“否定”以及过度假定错误传播。为应对这些问题，我们提出了一种有效的“回溯”策略，重新审视图像以核实初始推理中的每条信息。“回溯”策略能将批判和修正性能显著提升，最高可达 13.5%。

> The ability of large vision-language models (LVLMs) to critique and correct their reasoning is an essential building block towards their self-improvement. However, a systematic analysis of such capabilities in LVLMs is still lacking. We propose VISCO, the first benchmark to extensively analyze the fine-grained critique and correction capabilities of LVLMs. Compared to existing work that uses a single scalar value to critique the entire reasoning [4], VISCO features dense and fine-grained critique, requiring LVLMs to evaluate the correctness of each step in the chain-of-thought and provide natural language explanations to support their judgments. Extensive evaluation of 24 LVLMs demonstrates that human-written critiques significantly enhance the performance after correction, showcasing the potential of the self-improvement strategy. However, the model-generated critiques are less helpful and sometimes detrimental to the performance, suggesting that critique is the crucial bottleneck. We identified three common patterns in critique failures: failure to critique visual perception, reluctance to "say no", and exaggerated assumption of error propagation. To address these issues, we propose an effective LookBack strategy that revisits the image to verify each piece of information in the initial reasoning. LookBack significantly improves critique and correction performance by up to 13.5%.

[Arxiv](https://arxiv.org/abs/2412.02172)