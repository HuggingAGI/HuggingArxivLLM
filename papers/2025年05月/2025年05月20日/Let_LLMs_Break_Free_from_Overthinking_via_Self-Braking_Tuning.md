# 解绑 LLM 的过度思考，释放其潜能——自我制动调优新方案

发布时间：2025年05月20日

`LLM应用` `人工智能` `计算效率`

> Let LLMs Break Free from Overthinking via Self-Braking Tuning

# 摘要

> 大型推理模型（LRMs），如 OpenAI o1 和 DeepSeek-R1，通过生成更长的推理链显著提升了推理能力，并在多种任务中展现出卓越性能。然而，这种提升伴随着生成过程中冗余推理的激增，导致高昂计算开销并加剧了过度思考问题。尽管现有方法多致力于解决过度思考，但大多依赖外部干预。本文提出全新框架——自我制动调优（SBT），从模型自我调节推理过程的角度出发，摆脱对外部控制的依赖。我们基于标准答案构建了一套过度思考识别指标，并设计了一种系统化方法来检测冗余推理。该方法能够精准识别推理轨迹中的多余步骤，生成用于学习自我调节行为的训练信号。在此基础上，我们开发了一种构建具有自适应推理长度的数据策略，并引入创新刹车提示机制，使模型能够自然学习何时在适当节点终止推理。在数学基准测试（AIME、AMC、MATH500、GSM8K）上的实验表明，相较于无约束模型，我们的方法在保持可比准确性的前提下，将token消耗减少了高达60%。

> Large reasoning models (LRMs), such as OpenAI o1 and DeepSeek-R1, have significantly enhanced their reasoning capabilities by generating longer chains of thought, demonstrating outstanding performance across a variety of tasks. However, this performance gain comes at the cost of a substantial increase in redundant reasoning during the generation process, leading to high computational overhead and exacerbating the issue of overthinking. Although numerous existing approaches aim to address the problem of overthinking, they often rely on external interventions. In this paper, we propose a novel framework, Self-Braking Tuning (SBT), which tackles overthinking from the perspective of allowing the model to regulate its own reasoning process, thus eliminating the reliance on external control mechanisms. We construct a set of overthinking identification metrics based on standard answers and design a systematic method to detect redundant reasoning. This method accurately identifies unnecessary steps within the reasoning trajectory and generates training signals for learning self-regulation behaviors. Building on this foundation, we develop a complete strategy for constructing data with adaptive reasoning lengths and introduce an innovative braking prompt mechanism that enables the model to naturally learn when to terminate reasoning at an appropriate point. Experiments across mathematical benchmarks (AIME, AMC, MATH500, GSM8K) demonstrate that our method reduces token consumption by up to 60% while maintaining comparable accuracy to unconstrained models.

[Arxiv](https://arxiv.org/abs/2505.14604)