# 图像多模态模型的入侵：针对视频多模态大语言模型的可转移攻击

发布时间：2025年01月01日

`LLM应用

理由：这篇论文主要探讨了视频多模态大模型（V-MLLMs）在视频-文本任务中的对抗样本攻击问题，并提出了一种新的攻击方法（I2V-MLLM）。虽然涉及对抗攻击和模型脆弱性，但其核心关注点是如何利用多模态大模型（LLM）在实际应用中的表现和安全性。因此，这篇论文应归类为LLM应用。` `视频处理` `网络安全`

> Image-based Multimodal Models as Intruders: Transferable Multimodal Attacks on Video-based MLLMs

# 摘要

> # 摘要
视频多模态大模型（V-MLLMs）在视频-文本任务中容易受到对抗样本的攻击，但对抗视频在未知模型中的可迁移性——这一现实场景——尚未被充分研究。本文首次探讨了对抗视频样本在V-MLLMs中的迁移能力。我们发现，现有对抗攻击方法在V-MLLMs的黑盒场景中存在明显局限，原因包括：（1）视频特征扰动泛化能力不足，（2）仅关注稀疏关键帧，（3）未能融合多模态信息。为突破这些限制并深入理解V-MLLMs的黑盒脆弱性，我们提出了图像到视频MLLM（I2V-MLLM）攻击。该方法利用图像多模态模型（IMM）作为代理模型生成对抗视频样本，通过融合多模态交互与时间信息，破坏潜在空间中的视频表示，提升对抗迁移能力。此外，我们还引入了扰动传播技术，以应对不同帧采样策略。实验表明，我们的方法生成的对抗样本在多个视频-文本任务中表现出强大的跨模型迁移能力。与白盒攻击相比，基于BLIP-2代理模型的黑盒攻击在MSVD-QA和MSRVTT-QA的VideoQA任务中分别取得了55.48%和58.26%的平均攻击成功率，表现优异。代码将在论文录用后开源。

> Video-based multimodal large language models (V-MLLMs) have shown vulnerability to adversarial examples in video-text multimodal tasks. However, the transferability of adversarial videos to unseen models--a common and practical real world scenario--remains unexplored. In this paper, we pioneer an investigation into the transferability of adversarial video samples across V-MLLMs. We find that existing adversarial attack methods face significant limitations when applied in black-box settings for V-MLLMs, which we attribute to the following shortcomings: (1) lacking generalization in perturbing video features, (2) focusing only on sparse key-frames, and (3) failing to integrate multimodal information. To address these limitations and deepen the understanding of V-MLLM vulnerabilities in black-box scenarios, we introduce the Image-to-Video MLLM (I2V-MLLM) attack. In I2V-MLLM, we utilize an image-based multimodal model (IMM) as a surrogate model to craft adversarial video samples. Multimodal interactions and temporal information are integrated to disrupt video representations within the latent space, improving adversarial transferability. In addition, a perturbation propagation technique is introduced to handle different unknown frame sampling strategies. Experimental results demonstrate that our method can generate adversarial examples that exhibit strong transferability across different V-MLLMs on multiple video-text multimodal tasks. Compared to white-box attacks on these models, our black-box attacks (using BLIP-2 as surrogate model) achieve competitive performance, with average attack success rates of 55.48% on MSVD-QA and 58.26% on MSRVTT-QA for VideoQA tasks, respectively. Our code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2501.01042)