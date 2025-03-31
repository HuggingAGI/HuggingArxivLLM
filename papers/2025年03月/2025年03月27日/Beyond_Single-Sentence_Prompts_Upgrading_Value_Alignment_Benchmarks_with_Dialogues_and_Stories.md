# 超越单句提示：以对话与故事提升价值对齐评测基准

发布时间：2025年03月27日

`LLM应用` `AI伦理`

> Beyond Single-Sentence Prompts: Upgrading Value Alignment Benchmarks with Dialogues and Stories

# 摘要

> 评估大型语言模型（LLMs）的价值对齐，传统方法主要依赖单句对抗性提示，通过直接抛出涉及道德敏感或争议性问题来测试模型。然而，随着AI安全技术的快速发展，模型越来越擅长规避这些直接测试，使得传统方法在揭示潜在偏见和伦理立场方面效果有限。

为了解决这一问题，我们提出了一种升级的价值对齐基准测试，突破了单句提示的局限，引入了多轮对话和叙事场景。这种方法增强了评估的隐蔽性和对抗性，使其更能突破现代LLMs中常见的表面防护机制。

我们设计并实现了一个包含对话陷阱和道德模糊叙事的测试集，系统性地评估LLMs在更复杂和语境丰富的场景下的表现。实验结果表明，这种增强型评估方法能够有效揭示传统单次测试中未能察觉的潜在偏见。

我们的发现突显了在LLMs的价值对齐评估中采用情境化和动态化测试的必要性，为更复杂和现实的AI伦理与安全评估奠定了基础。

> Evaluating the value alignment of large language models (LLMs) has traditionally relied on single-sentence adversarial prompts, which directly probe models with ethically sensitive or controversial questions. However, with the rapid advancements in AI safety techniques, models have become increasingly adept at circumventing these straightforward tests, limiting their effectiveness in revealing underlying biases and ethical stances. To address this limitation, we propose an upgraded value alignment benchmark that moves beyond single-sentence prompts by incorporating multi-turn dialogues and narrative-based scenarios. This approach enhances the stealth and adversarial nature of the evaluation, making it more robust against superficial safeguards implemented in modern LLMs. We design and implement a dataset that includes conversational traps and ethically ambiguous storytelling, systematically assessing LLMs' responses in more nuanced and context-rich settings. Experimental results demonstrate that this enhanced methodology can effectively expose latent biases that remain undetected in traditional single-shot evaluations. Our findings highlight the necessity of contextual and dynamic testing for value alignment in LLMs, paving the way for more sophisticated and realistic assessments of AI ethics and safety.

[Arxiv](https://arxiv.org/abs/2503.22115)