# # 超越越狱：揭示LLM安全风险新威胁：更隐蔽、更广泛，源自对齐失败

发布时间：2025年06月08日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在实际应用中的安全性问题，特别是隐性危害，提出了新的评估基准和攻击方法。它属于LLM应用层面的研究，因为它关注模型在现实场景中的安全性和评估方法。` `人工智能` `模型安全`

> Beyond Jailbreaks: Revealing Stealthier and Broader LLM Security Risks Stemming from Alignment Failures

# 摘要

> 大型语言模型 (LLMs) 在现实应用中的部署日益增多，随之而来的是对其安全性的关注。尽管越狱攻击揭示了模型在面对明显有害查询时的缺陷，但它们忽视了一个关键风险：对看似无害的输入给出错误回答可能带来危险，并造成实际伤害（隐性危害）。我们通过结构化的象限视角，基于输出的事实性和输入的无害性，系统性地重新构建了 LLM 的风险格局，揭示了一个被忽视的高风险区域。为填补这一研究空白，我们提出了 JailFlipBench，一个旨在捕捉隐性危害的基准，涵盖单模态、多模态和事实扩展场景，并采用多样化的评估指标。我们进一步开发了初步的 JailFlip 攻击方法，并对多个开源和黑盒 LLM 进行了全面评估，结果显示隐性危害构成了即时且紧迫的现实风险，呼吁对 LLM 的安全性评估和对齐进行更广泛的探索，超越传统的越狱范式。

> Large language models (LLMs) are increasingly deployed in real-world applications, raising concerns about their security. While jailbreak attacks highlight failures under overtly harmful queries, they overlook a critical risk: incorrectly answering harmless-looking inputs can be dangerous and cause real-world harm (Implicit Harm). We systematically reformulate the LLM risk landscape through a structured quadrant perspective based on output factuality and input harmlessness, uncovering an overlooked high-risk region. To investigate this gap, we propose JailFlipBench, a benchmark aims to capture implicit harm, spanning single-modal, multimodal, and factual extension scenarios with diverse evaluation metrics. We further develop initial JailFlip attack methodologies and conduct comprehensive evaluations across multiple open-source and black-box LLMs, show that implicit harm present immediate and urgent real-world risks, calling for broader LLM safety assessments and alignment beyond conventional jailbreak paradigms.

[Arxiv](https://arxiv.org/abs/2506.07402)