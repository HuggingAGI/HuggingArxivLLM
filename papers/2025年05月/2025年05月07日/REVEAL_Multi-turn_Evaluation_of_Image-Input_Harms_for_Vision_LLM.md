# # REVEAL —— 视觉LLM的图像输入风险多轮评估

发布时间：2025年05月07日

`LLM应用` `人工智能` `安全评估`

> REVEAL: Multi-turn Evaluation of Image-Input Harms for Vision LLM

# 摘要

> 视觉大语言模型（VLLMs）在人工智能领域取得了革命性进展，通过结合图像处理与文本理解能力，显著提升了用户体验并拓宽了应用场景。然而，其复杂性也带来了新的安全与伦理挑战，尤其是在多模态和多轮对话场景中。传统针对文本单轮交互的安全评估框架已无法应对这些复杂挑战。为解决这一问题，我们提出了REVEAL（负责任的视觉增强AI大语言模型评估）框架，这是一个用于评估VLLMs中图像输入危害的可扩展、自动化解决方案。
    REVEAL框架整合了自动化图像挖掘、合成对抗数据生成、基于渐强攻击策略的多轮对话扩展，以及通过GPT-4o等评估器进行的全面危害评估。我们对GPT-4o、Llama-3.2、Qwen2-VL、Phi3.5V和Pixtral五种先进VLLMs进行了全面测试，重点关注性危害、暴力和虚假信息三大危害类别。研究发现，多轮交互场景下模型的缺陷率显著高于单轮评估，表明VLLMs在复杂对话场景中存在更深的安全漏洞。其中，GPT-4o在我们的安全-可用性指数（SUI）评估中表现最为均衡， Pixtral紧随其后。此外，虚假信息生成成为亟需加强语境防御的关键领域。值得注意的是，Llama-3.2在多轮对话场景中的缺陷率最高（16.55%），而Qwen2-VL在多轮对话中的拒绝率最高（19.1%）。

> Vision Large Language Models (VLLMs) represent a significant advancement in artificial intelligence by integrating image-processing capabilities with textual understanding, thereby enhancing user interactions and expanding application domains. However, their increased complexity introduces novel safety and ethical challenges, particularly in multi-modal and multi-turn conversations. Traditional safety evaluation frameworks, designed for text-based, single-turn interactions, are inadequate for addressing these complexities. To bridge this gap, we introduce the REVEAL (Responsible Evaluation of Vision-Enabled AI LLMs) Framework, a scalable and automated pipeline for evaluating image-input harms in VLLMs. REVEAL includes automated image mining, synthetic adversarial data generation, multi-turn conversational expansion using crescendo attack strategies, and comprehensive harm assessment through evaluators like GPT-4o.
  We extensively evaluated five state-of-the-art VLLMs, GPT-4o, Llama-3.2, Qwen2-VL, Phi3.5V, and Pixtral, across three important harm categories: sexual harm, violence, and misinformation. Our findings reveal that multi-turn interactions result in significantly higher defect rates compared to single-turn evaluations, highlighting deeper vulnerabilities in VLLMs. Notably, GPT-4o demonstrated the most balanced performance as measured by our Safety-Usability Index (SUI) followed closely by Pixtral. Additionally, misinformation emerged as a critical area requiring enhanced contextual defenses. Llama-3.2 exhibited the highest MT defect rate ($16.55 \%$) while Qwen2-VL showed the highest MT refusal rate ($19.1 \%$).

[Arxiv](https://arxiv.org/abs/2505.04673)