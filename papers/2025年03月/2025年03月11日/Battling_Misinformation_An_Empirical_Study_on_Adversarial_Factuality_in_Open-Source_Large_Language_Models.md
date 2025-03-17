# 抗击错误信息：开源大型语言模型中的对抗事实性研究

发布时间：2025年03月11日

`LLM应用` `人工智能`

> Battling Misinformation: An Empirical Study on Adversarial Factuality in Open-Source Large Language Models

# 摘要

> 对抗性事实性是指对手蓄意在输入提示中插入错误信息，其特点是具有不同层次的表达自信水平。在本研究中，我们系统性地评估了多个开源大型语言模型（LLMs）在面对此类对抗性输入时的表现。我们考虑了三个层次的对抗性自信水平：强烈自信、中等自信和有限自信。我们的分析涵盖了八种大型语言模型：LLaMA 3.1（8B）、Phi 3（3.8B）、Qwen 2.5（7B）、Deepseek-v2（16B）、Gemma2（9B）、Falcon（7B）、Mistrallite（7B）和LLaVA（7B）。实证结果表明，LLaMA 3.1（8B）在检测对抗性输入方面表现出强大的能力，而Falcon（7B）则表现出相对较低的性能。值得注意的是，对于大多数模型而言，检测成功率随着对手自信水平的降低而提高；然而，这一趋势在LLaMA 3.1（8B）和Phi 3（3.8B）中被逆转，即对抗性自信水平的降低对应着检测性能的减弱。通过对引发最高和最低成功率攻击的查询进行进一步分析，我们发现对抗性攻击在针对较少被引用或较为模糊的信息时更为有效。

> Adversarial factuality refers to the deliberate insertion of misinformation into input prompts by an adversary, characterized by varying levels of expressed confidence. In this study, we systematically evaluate the performance of several open-source large language models (LLMs) when exposed to such adversarial inputs. Three tiers of adversarial confidence are considered: strongly confident, moderately confident, and limited confidence. Our analysis encompasses eight LLMs: LLaMA 3.1 (8B), Phi 3 (3.8B), Qwen 2.5 (7B), Deepseek-v2 (16B), Gemma2 (9B), Falcon (7B), Mistrallite (7B), and LLaVA (7B). Empirical results indicate that LLaMA 3.1 (8B) exhibits a robust capability in detecting adversarial inputs, whereas Falcon (7B) shows comparatively lower performance. Notably, for the majority of the models, detection success improves as the adversary's confidence decreases; however, this trend is reversed for LLaMA 3.1 (8B) and Phi 3 (3.8B), where a reduction in adversarial confidence corresponds with diminished detection performance. Further analysis of the queries that elicited the highest and lowest rates of successful attacks reveals that adversarial attacks are more effective when targeting less commonly referenced or obscure information.

[Arxiv](https://arxiv.org/abs/2503.10690)