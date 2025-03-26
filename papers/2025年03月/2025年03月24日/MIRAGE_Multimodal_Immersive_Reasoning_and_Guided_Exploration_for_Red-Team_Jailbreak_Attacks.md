# MIRAGE：多模态沉浸式推理与引导探索，用于红队越狱攻击

发布时间：2025年03月24日

`LLM应用` `人工智能安全`

> MIRAGE: Multimodal Immersive Reasoning and Guided Exploration for Red-Team Jailbreak Attacks

# 摘要

> 尽管在过滤有害文本输入的安全机制方面取得了显著进展，但多模态大型语言模型（MLLMs）仍然容易受到多模态越狱攻击的威胁，这些攻击利用了模型的跨模态推理能力。我们提出了MIRAGE，一个创新的多模态越狱框架，通过叙事驱动的上下文和角色沉浸，成功绕过多模态大型语言模型的安全防线。通过将有害查询分解为环境、角色和行动三元组，MIRAGE利用Stable Diffusion生成包含图像和文本的多轮视觉叙事序列，引导目标模型进入一个引人入胜的侦探故事。这一过程逐步削弱模型的防御机制，并通过结构化的上下文线索引导模型推理，最终诱使其产生有害回应。在对六种主流MLLMs的广泛实验中，MIRAGE实现了最先进的攻击效果，攻击成功率比最佳基线方法提高了17.5%。此外，我们发现角色沉浸和结构化的语义重构能够激活模型的内在偏见，使其自发违反伦理保护措施。这些发现不仅揭示了当前多模态安全机制的脆弱性，也凸显了开发更强大的跨模态威胁防御机制的迫切需求。

> While safety mechanisms have significantly progressed in filtering harmful text inputs, MLLMs remain vulnerable to multimodal jailbreaks that exploit their cross-modal reasoning capabilities. We present MIRAGE, a novel multimodal jailbreak framework that exploits narrative-driven context and role immersion to circumvent safety mechanisms in Multimodal Large Language Models (MLLMs). By systematically decomposing the toxic query into environment, role, and action triplets, MIRAGE constructs a multi-turn visual storytelling sequence of images and text using Stable Diffusion, guiding the target model through an engaging detective narrative. This process progressively lowers the model's defences and subtly guides its reasoning through structured contextual cues, ultimately eliciting harmful responses. In extensive experiments on the selected datasets with six mainstream MLLMs, MIRAGE achieves state-of-the-art performance, improving attack success rates by up to 17.5% over the best baselines. Moreover, we demonstrate that role immersion and structured semantic reconstruction can activate inherent model biases, facilitating the model's spontaneous violation of ethical safeguards. These results highlight critical weaknesses in current multimodal safety mechanisms and underscore the urgent need for more robust defences against cross-modal threats.

[Arxiv](https://arxiv.org/abs/2503.19134)