# 借助多模态链接来突破大型视觉语言模型

发布时间：2024年12月03日

`LLM应用` `视觉语言模型` `信息安全`

> Jailbreak Large Vision-Language Models Through Multi-Modal Linkage

# 摘要

> 随着大型视觉语言模型（VLMs）的大幅进步，人们对其可能被误用和滥用的担忧与日俱增。先前的研究指出，VLMs 易受越狱攻击，精心设计的输入会致使模型生成违背道德和法律标准的内容。然而，由于有害内容过度暴露且缺乏隐蔽的恶意引导，现有方法难以应对像 GPT-4o 这般先进的 VLMs。在本项工作中，我们提出了一种全新的越狱攻击框架：多模态链接（MML）攻击。受密码学启发，MML 通过在文本和图像模式间进行加密和解密过程，以减少恶意信息的过度暴露。为了暗中使模型的输出与恶意意图相符，MML 运用了一种名为“邪恶对齐”的技术，将攻击置于视频游戏制作场景之中。全面的实验证实了 MML 的有效性。具体来说，MML 对 GPT-4o 的越狱攻击成功率在 SafeBench 上达 97.80%，在 MM-SafeBench 上达 98.81%，在 HADES-Dataset 上达 99.07%。我们的代码可在 https://github.com/wangyu-ovo/MML 获取。

> With the significant advancement of Large Vision-Language Models (VLMs), concerns about their potential misuse and abuse have grown rapidly. Previous studies have highlighted VLMs' vulnerability to jailbreak attacks, where carefully crafted inputs can lead the model to produce content that violates ethical and legal standards. However, existing methods struggle against state-of-the-art VLMs like GPT-4o, due to the over-exposure of harmful content and lack of stealthy malicious guidance. In this work, we propose a novel jailbreak attack framework: Multi-Modal Linkage (MML) Attack. Drawing inspiration from cryptography, MML utilizes an encryption-decryption process across text and image modalities to mitigate over-exposure of malicious information. To align the model's output with malicious intent covertly, MML employs a technique called "evil alignment", framing the attack within a video game production scenario. Comprehensive experiments demonstrate MML's effectiveness. Specifically, MML jailbreaks GPT-4o with attack success rates of 97.80% on SafeBench, 98.81% on MM-SafeBench and 99.07% on HADES-Dataset. Our code is available at https://github.com/wangyu-ovo/MML

[Arxiv](https://arxiv.org/abs/2412.00473)