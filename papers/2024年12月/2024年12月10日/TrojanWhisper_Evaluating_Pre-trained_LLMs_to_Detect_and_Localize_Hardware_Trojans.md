# TrojanWhisper：对预训练的 LLMs 进行评估，以检测和定位硬件木马

发布时间：2024年12月10日

`LLM应用` `硬件安全` `芯片检测`

> TrojanWhisper: Evaluating Pre-trained LLMs to Detect and Localize Hardware Trojans

# 摘要

> 现有的硬件木马（HT）检测手段存在若干关键局限：逻辑测试在大型设计的可扩展性和覆盖范围上遭遇难题，侧信道分析依赖黄金参考芯片，形式验证方法受困于状态空间爆炸。大型语言模型（LLMs）的出现为HT检测开辟了颇具前景的新方向，借助其自然语言理解与推理能力。本文首次探究了通用LLMs在检测寄存器传输级（RTL）设计中各类HT（涵盖SRAM、AES和UART模块）的潜力。我们为实现此目标提出了一种创新工具，系统评估了前沿的LLMs（GPT-4o、Gemini 1.5 pro和Llama 3.1）在未经事先微调情况下检测HT的能力。为应对潜在的训练数据偏差，该工具采用了扰动技术，比如变量名混淆和设计重构，让案例对于所使用的LLMs更具复杂性。我们的实验评估显示，在基线场景中，GPT-4o和Gemini 1.5 pro检测率堪称完美（精度/召回率均为100%），这两个模型的触发线覆盖率（TLC：0.82 - 0.98）均高于有效负载线覆盖率（PLC：0.32 - 0.46）。在代码扰动情况下，尽管Gemini 1.5 pro保持了完美的检测性能（100%/100%），但GPT-4o（100%/85.7%）和Llama 3.1（66.7%/85.7%）的检测率有所降低，并且所有模型在定位触发和有效负载方面的准确性都有所下降。本文验证了LLMs方法在硬件安全应用中的潜力，指明了未来有待改进的方向。

> Existing Hardware Trojans (HT) detection methods face several critical limitations: logic testing struggles with scalability and coverage for large designs, side-channel analysis requires golden reference chips, and formal verification methods suffer from state-space explosion. The emergence of Large Language Models (LLMs) offers a promising new direction for HT detection by leveraging their natural language understanding and reasoning capabilities. For the first time, this paper explores the potential of general-purpose LLMs in detecting various HTs inserted in Register Transfer Level (RTL) designs, including SRAM, AES, and UART modules. We propose a novel tool for this goal that systematically assesses state-of-the-art LLMs (GPT-4o, Gemini 1.5 pro, and Llama 3.1) in detecting HTs without prior fine-tuning. To address potential training data bias, the tool implements perturbation techniques, i.e., variable name obfuscation, and design restructuring, that make the cases more sophisticated for the used LLMs. Our experimental evaluation demonstrates perfect detection rates by GPT-4o and Gemini 1.5 pro in baseline scenarios (100%/100% precision/recall), with both models achieving better trigger line coverage (TLC: 0.82-0.98) than payload line coverage (PLC: 0.32-0.46). Under code perturbation, while Gemini 1.5 pro maintains perfect detection performance (100%/100%), GPT-4o (100%/85.7%) and Llama 3.1 (66.7%/85.7%) show some degradation in detection rates, and all models experience decreased accuracy in localizing both triggers and payloads. This paper validates the potential of LLM approaches for hardware security applications, highlighting areas for future improvement.

[Arxiv](https://arxiv.org/abs/2412.07636)