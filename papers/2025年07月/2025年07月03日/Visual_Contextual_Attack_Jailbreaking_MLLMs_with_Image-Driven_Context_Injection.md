# 视觉上下文攻击：通过图像驱动的上下文注入破解MLLMs

发布时间：2025年07月03日

`LLM应用` `视觉安全` `网络安全`

> Visual Contextual Attack: Jailbreaking MLLMs with Image-Driven Context Injection

# 摘要

> 强大的视觉语言能力推动了多模态大型语言模型 (MLLMs) 在现实应用中的广泛应用。然而，视觉模态的安全漏洞为开放世界环境中的模型部署带来了严峻挑战。近期研究通过将有害文字语义直接嵌入视觉输入，成功诱导目标 MLLMs 产生有害响应。但现有方法中，视觉模态主要作为不安全行为的触发器，常存在语义模糊且缺乏现实场景支撑的问题。本研究提出了一种全新设置：视觉中心越狱，其中视觉信息在构建完整且现实的越狱场景中扮演核心角色。基于此，我们开发了 VisCo（视觉上下文）攻击方法。VisCo 通过四种独特的视觉聚焦策略构建上下文对话，并在必要时动态生成辅助图像，构建视觉中心越狱场景。为提升攻击效果，VisCo 集成自动毒性模糊处理和语义优化，生成可靠的攻击提示，触发目标黑盒 MLLMs 产生有害响应。实验结果显示，VisCo 在 MM-SafetyBench 数据集上针对 GPT-4o 实现了 4.78 的毒性评分和 85% 的攻击成功率 (ASR)，显著优于基线方法（毒性评分 2.48，ASR 22.2%）。代码已开源，地址为 https://github.com/Dtc7w3PQ/Visco-Attack。

> With the emergence of strong visual-language capabilities, multimodal large language models (MLLMs) have demonstrated tremendous potential for real-world applications. However, the security vulnerabilities exhibited by the visual modality pose significant challenges to deploying such models in open-world environments. Recent studies have successfully induced harmful responses from target MLLMs by encoding harmful textual semantics directly into visual inputs. However, in these approaches, the visual modality primarily serves as a trigger for unsafe behavior, often exhibiting semantic ambiguity and lacking grounding in realistic scenarios. In this work, we define a novel setting: visual-centric jailbreak, where visual information serves as a necessary component in constructing a complete and realistic jailbreak context. Building on this setting, we propose the VisCo (Visual Contextual) Attack. VisCo fabricates contextual dialogue using four distinct visual-focused strategies, dynamically generating auxiliary images when necessary to construct a visual-centric jailbreak scenario. To maximize attack effectiveness, it incorporates automatic toxicity obfuscation and semantic refinement to produce a final attack prompt that reliably triggers harmful responses from the target black-box MLLMs. Specifically, VisCo achieves a toxicity score of 4.78 and an Attack Success Rate (ASR) of 85% on MM-SafetyBench against GPT-4o, significantly outperforming the baseline, which performs a toxicity score of 2.48 and an ASR of 22.2%. The code is available at https://github.com/Dtc7w3PQ/Visco-Attack.

[Arxiv](https://arxiv.org/abs/2507.02844)