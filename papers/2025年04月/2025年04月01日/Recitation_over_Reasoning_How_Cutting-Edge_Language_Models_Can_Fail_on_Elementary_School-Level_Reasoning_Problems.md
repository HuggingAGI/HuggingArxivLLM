# 背诵取代推理：前沿语言模型如何在小学推理题上栽跟头？

发布时间：2025年04月01日

`LLM理论` `人工智能` `模型评估`

> Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?

# 摘要

> 近年来，大型语言模型（LLMs）的基准测试难度从小学水平迅速提升到前沿问题，为研究人员创造了一个奇迹，使我们距离超越人类智能仅有咫尺之遥。然而，LLMs令人瞩目的推理能力是否真正源于符合人类标准的真实智能，还是仅仅在互联网级别上复述了训练过程中见过的解决方案？为了研究这个问题，我们提出了RoR-Bench，这是一个新型的多模态基准测试，用于检测当LLMs被要求解决简单的推理问题但条件略有变化时的复述行为，并在我们的基准测试上进行实证分析。令人惊讶的是，我们发现现有的 cutting-edge LLMs 一致表现出极其严重的复述行为；只需改变条件中的一个短语，像 OpenAI-o1 和 DeepSeek-R1 这样的顶级模型在小学水平的算术和推理问题上的性能就会下降 60%。这一发现对 LLM 社区来说是一个警钟，迫使我们重新评估 cutting-edge LLMs 的真实智能水平。

> The rapid escalation from elementary school-level to frontier problems of the difficulty for LLM benchmarks in recent years have weaved a miracle for researchers that we are only inches away from surpassing human intelligence. However, is the LLMs' remarkable reasoning ability indeed comes from true intelligence by human standards, or are they simply reciting solutions witnessed during training at an Internet level? To study this problem, we propose RoR-Bench, a novel, multi-modal benchmark for detecting LLM's recitation behavior when asked simple reasoning problems but with conditions subtly shifted, and conduct empirical analysis on our benchmark. Surprisingly, we found existing cutting-edge LLMs unanimously exhibits extremely severe recitation behavior; by changing one phrase in the condition, top models such as OpenAI-o1 and DeepSeek-R1 can suffer $60\%$ performance loss on elementary school-level arithmetic and reasoning problems. Such findings are a wake-up call to the LLM community that compels us to re-evaluate the true intelligence level of cutting-edge LLMs.

[Arxiv](https://arxiv.org/abs/2504.00509)