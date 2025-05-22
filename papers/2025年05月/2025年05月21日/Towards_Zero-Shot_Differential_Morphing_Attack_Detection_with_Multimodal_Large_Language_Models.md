# 基于多模态大型语言模型的零样本差异形变攻击检测方法探索

发布时间：2025年05月21日

`LLM应用` `生物识别` `计算机视觉`

> Towards Zero-Shot Differential Morphing Attack Detection with Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（LLMs）的强大功能为提升形变攻击检测（MAD）的准确性和可解释性提供了一种充满潜力的解决方案，尤其在现实世界的生物识别应用中。本研究首次将LLMs应用于差异形变攻击检测（D-MAD），并基于真实生物识别数据进行了深入探索。为了更好地发挥这些模型的潜力，我们设计了基于链式思维（CoT）的提示方法，以降低无法回答的概率并增强决策的推理能力。我们的主要贡献包括：

- 首次将多模态LLMs应用于D-MAD的实证研究
- 通过基于CoT的提示工程提升响应的可靠性和可解释性
- 基于54个个体在护照注册场景下的数据，进行了全面的定性和定量基准测试
- 对两种多模态LLMs（ChatGPT-4o与Gemini）进行了对比分析，揭示了它们在形变攻击检测准确性与决策透明度方面的差异

实验结果表明，ChatGPT-4o在检测精度上优于Gemini，尤其是在对抗基于GAN的形变攻击时表现突出，但两种模型在面对更具挑战性的条件时均显乏力。尽管Gemini提供了更加一致的解释，但ChatGPT-4o展现出更强的抗干扰能力，尽管其无法回答的概率也相对较高。

> Leveraging the power of multimodal large language models (LLMs) offers a promising approach to enhancing the accuracy and interpretability of morphing attack detection (MAD), especially in real-world biometric applications. This work introduces the use of LLMs for differential morphing attack detection (D-MAD). To the best of our knowledge, this is the first study to employ multimodal LLMs to D-MAD using real biometric data. To effectively utilize these models, we design Chain-of-Thought (CoT)-based prompts to reduce failure-to-answer rates and enhance the reasoning behind decisions. Our contributions include: (1) the first application of multimodal LLMs for D-MAD using real data subjects, (2) CoT-based prompt engineering to improve response reliability and explainability, (3) comprehensive qualitative and quantitative benchmarking of LLM performance using data from 54 individuals captured in passport enrollment scenarios, and (4) comparative analysis of two multimodal LLMs: ChatGPT-4o and Gemini providing insights into their morphing attack detection accuracy and decision transparency. Experimental results show that ChatGPT-4o outperforms Gemini in detection accuracy, especially against GAN-based morphs, though both models struggle under challenging conditions. While Gemini offers more consistent explanations, ChatGPT-4o is more resilient but prone to a higher failure-to-answer rate.

[Arxiv](https://arxiv.org/abs/2505.15332)