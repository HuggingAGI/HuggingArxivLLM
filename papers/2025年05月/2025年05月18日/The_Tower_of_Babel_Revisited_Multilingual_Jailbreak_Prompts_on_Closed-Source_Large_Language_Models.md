# 巴别塔再探：闭源大语言模型的多语言越狱提示

发布时间：2025年05月18日

`LLM应用` `AI安全`

> The Tower of Babel Revisited: Multilingual Jailbreak Prompts on Closed-Source Large Language Models

# 摘要

> 大型语言模型（LLMs）在多领域广泛应用的同时，仍面临对抗性提示注入的威胁。不同于现有研究对开源模型的关注，我们聚焦于多语言攻击场景下的闭源LLMs前沿技术。我们开发了一种开创性的综合对抗框架，整合多种攻击技术，系统性评估GPT-4o、DeepSeek-R1、Gemini-1.5-Pro和Qwen-Max等前沿专有解决方案。评估涵盖英汉两种语言下的六大类安全内容，针对32种越狱攻击类型生成了38,400条响应。通过攻击成功率（ASR）量化评估，从提示设计、模型架构和语言环境三个维度进行分析。结果显示，Qwen-Max最易受攻击，而GPT-4o防御能力最强。值得注意的是，中文提示的攻击成功率始终高于英文版本，且我们的创新性双面攻击技术在所有模型中表现最为突出。这项研究强调了语言感知对齐和强健跨语言防御在LLMs中的重要性，我们期待它能激励各界共同打造更加强健和包容的AI系统。


> Large language models (LLMs) have seen widespread applications across various domains, yet remain vulnerable to adversarial prompt injections. While most existing research on jailbreak attacks and hallucination phenomena has focused primarily on open-source models, we investigate the frontier of closed-source LLMs under multilingual attack scenarios. We present a first-of-its-kind integrated adversarial framework that leverages diverse attack techniques to systematically evaluate frontier proprietary solutions, including GPT-4o, DeepSeek-R1, Gemini-1.5-Pro, and Qwen-Max. Our evaluation spans six categories of security contents in both English and Chinese, generating 38,400 responses across 32 types of jailbreak attacks. Attack success rate (ASR) is utilized as the quantitative metric to assess performance from three dimensions: prompt design, model architecture, and language environment. Our findings suggest that Qwen-Max is the most vulnerable, while GPT-4o shows the strongest defense. Notably, prompts in Chinese consistently yield higher ASRs than their English counterparts, and our novel Two-Sides attack technique proves to be the most effective across all models. This work highlights a dire need for language-aware alignment and robust cross-lingual defenses in LLMs, and we hope it will inspire researchers, developers, and policymakers toward more robust and inclusive AI systems.

[Arxiv](https://arxiv.org/abs/2505.12287)