# “我很糟糕”：揭秘音频语言模型中的隐秘、通用且鲁棒的音频越狱

发布时间：2025年02月02日

`LLM应用

这篇论文主要探讨了多模态大型语言模型（特别是音频-语言模型）的安全性问题，特别是对抗性攻击和越狱攻击。虽然涉及了模型的安全性和对抗性攻击的理论，但其核心关注点在于如何应用这些模型以及如何在实际场景中防御这些攻击。因此，它更符合“LLM应用”这一分类。` `机器学习安全` `人机交互`

> "I am bad": Interpreting Stealthy, Universal and Robust Audio Jailbreaks in Audio-Language Models

# 摘要

> 多模态大型语言模型的崛起带来了创新的人机交互方式，但也伴随着机器学习安全领域的重大挑战。音频-语言模型（ALMs）因其语音交流的直观性而备受关注，然而对其故障模式的研究却寥寥无几。本文深入探讨了针对ALMs的音频越狱，重点研究了其绕过对齐机制的能力。我们构建了能够跨提示、任务和基础音频样本泛化的对抗性扰动，首次展示了音频模态中的通用越狱，并证明这些越狱在模拟现实环境中依然有效。除了揭示攻击的可行性，我们还分析了ALMs如何解读这些音频对抗样本，发现它们编码了难以察觉的第一人称有毒语音——这表明最有效的扰动在音频信号中嵌入了特定的语言特征，从而引发有毒输出。这些发现不仅深化了我们对多模态模型中不同模态交互的理解，还为防御对抗音频攻击提供了切实可行的建议。

> The rise of multimodal large language models has introduced innovative human-machine interaction paradigms but also significant challenges in machine learning safety. Audio-Language Models (ALMs) are especially relevant due to the intuitive nature of spoken communication, yet little is known about their failure modes. This paper explores audio jailbreaks targeting ALMs, focusing on their ability to bypass alignment mechanisms. We construct adversarial perturbations that generalize across prompts, tasks, and even base audio samples, demonstrating the first universal jailbreaks in the audio modality, and show that these remain effective in simulated real-world conditions. Beyond demonstrating attack feasibility, we analyze how ALMs interpret these audio adversarial examples and reveal them to encode imperceptible first-person toxic speech - suggesting that the most effective perturbations for eliciting toxic outputs specifically embed linguistic features within the audio signal. These results have important implications for understanding the interactions between different modalities in multimodal models, and offer actionable insights for enhancing defenses against adversarial audio attacks.

[Arxiv](https://arxiv.org/abs/2502.00718)