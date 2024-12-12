# 双重通用的对抗性扰动：凭借单个扰动就能在图像和文本方面欺骗视觉语言模型

发布时间：2024年12月11日

`LLM应用` `视觉语言` `对抗性攻击`

> Doubly-Universal Adversarial Perturbations: Deceiving Vision-Language Models Across Both Images and Text with a Single Perturbation

# 摘要

> 大型视觉语言模型（VLMs）将视觉编码器与大型语言模型（LLMs）相融合，在多模态任务中展现出非凡的性能。然而，这些模型易受对抗性攻击。在这些攻击中，通用对抗性扰动（UAPs）威力强大，单个优化的扰动就能在各种输入图像上误导模型。在本研究中，我们为 VLMs 引入了一种新型的 UAP：双重通用对抗性扰动（Doubly-UAP），能在图像和文本输入方面普遍欺骗 VLMs。为成功干扰视觉编码器的基本流程，我们剖析了注意力机制的核心组成部分。在认定中晚期层的值向量最为脆弱后，我们以无标签方式对冻结模型优化了 Doubly-UAP。尽管对于 LLM 而言它是个黑箱，但 Doubly-UAP 在 VLMs 上的攻击成功率颇高，在视觉语言任务中始终优于基线方法。大量的消融研究和分析进一步证实了 Doubly-UAP 的稳健性，并揭示了其对内部注意力机制的影响。

> Large Vision-Language Models (VLMs) have demonstrated remarkable performance across multimodal tasks by integrating vision encoders with large language models (LLMs). However, these models remain vulnerable to adversarial attacks. Among such attacks, Universal Adversarial Perturbations (UAPs) are especially powerful, as a single optimized perturbation can mislead the model across various input images. In this work, we introduce a novel UAP specifically designed for VLMs: the Doubly-Universal Adversarial Perturbation (Doubly-UAP), capable of universally deceiving VLMs across both image and text inputs. To successfully disrupt the vision encoder's fundamental process, we analyze the core components of the attention mechanism. After identifying value vectors in the middle-to-late layers as the most vulnerable, we optimize Doubly-UAP in a label-free manner with a frozen model. Despite being developed as a black-box to the LLM, Doubly-UAP achieves high attack success rates on VLMs, consistently outperforming baseline methods across vision-language tasks. Extensive ablation studies and analyses further demonstrate the robustness of Doubly-UAP and provide insights into how it influences internal attention mechanisms.

[Arxiv](https://arxiv.org/abs/2412.08108)