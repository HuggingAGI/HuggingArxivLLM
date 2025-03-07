# # 识别大型语言模型来源的黑箱挑战

发布时间：2025年03月06日

`LLM应用

论文摘要：大型语言模型（LLMs）的商业价值引发了对其未经授权使用的广泛关注。第三方通过微调定制LLMs并仅提供黑盒API访问，掩盖了未经授权的使用，增加了外部审计的难度。这种做法不仅加剧了不公平竞争，还违反了许可协议。为此，识别黑盒LLMs的来源是解决这一问题的关键。本文首先通过在30个LLMs和两个真实世界黑盒API上的实验，揭示了现有被动和主动识别方法的局限性。接着，我们提出了主动技术PlugAE，该技术通过优化连续空间中的对抗性令牌嵌入，并主动将其插入LLM中以实现追踪和识别。实验表明，PlugAE在识别微调衍生模型方面取得了显著改进。我们进一步呼吁建立法律框架和法规，以更好地应对未经授权使用LLMs带来的挑战。` `法律合规`

> The Challenge of Identifying the Origin of Black-Box Large Language Models

# 摘要

> 大型语言模型（LLMs）的商业价值引发了对其未经授权使用的广泛关注。第三方通过微调定制LLMs并仅提供黑盒API访问，掩盖了未经授权的使用，增加了外部审计的难度。这种做法不仅加剧了不公平竞争，还违反了许可协议。为此，识别黑盒LLMs的来源是解决这一问题的关键。本文首先通过在30个LLMs和两个真实世界黑盒API上的实验，揭示了现有被动和主动识别方法的局限性。接着，我们提出了主动技术PlugAE，该技术通过优化连续空间中的对抗性令牌嵌入，并主动将其插入LLM中以实现追踪和识别。实验表明，PlugAE在识别微调衍生模型方面取得了显著改进。我们进一步呼吁建立法律框架和法规，以更好地应对未经授权使用LLMs带来的挑战。

> The tremendous commercial potential of large language models (LLMs) has heightened concerns about their unauthorized use. Third parties can customize LLMs through fine-tuning and offer only black-box API access, effectively concealing unauthorized usage and complicating external auditing processes. This practice not only exacerbates unfair competition, but also violates licensing agreements. In response, identifying the origin of black-box LLMs is an intrinsic solution to this issue. In this paper, we first reveal the limitations of state-of-the-art passive and proactive identification methods with experiments on 30 LLMs and two real-world black-box APIs. Then, we propose the proactive technique, PlugAE, which optimizes adversarial token embeddings in a continuous space and proactively plugs them into the LLM for tracing and identification. The experiments show that PlugAE can achieve substantial improvement in identifying fine-tuned derivatives. We further advocate for legal frameworks and regulations to better address the challenges posed by the unauthorized use of LLMs.

[Arxiv](https://arxiv.org/abs/2503.04332)