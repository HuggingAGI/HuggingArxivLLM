# 多模态大型语言模型能否胜任深度伪造检测任务？

发布时间：2025年03月25日

`LLM应用

摘要中探讨了多模态大型语言模型在深度伪造图像检测中的应用，属于LLMs的实际应用研究。` `计算机视觉` `人工智能`

> Can Multi-modal (reasoning) LLMs work as deepfake detectors?

# 摘要

> 深度伪造检测在合成媒体日益复杂的背景下仍是关键挑战。本研究探索了包括OpenAI O1/4o、Gemini思考Flash 2等在内的12个最新多模态大型语言模型（LLMs）在深度伪造图像检测中的潜力。我们在多个数据集上进行了基准测试，包括近期发布的现实世界深度伪造图像。通过提示微调和深入分析模型推理路径，我们发现最佳多模态LLMs在零样本情况下表现优异，甚至超越传统检测方法在分布外数据集上的表现，而其他LLMs表现不佳。值得注意的是，模型版本更新和推理能力并未显著提升检测性能，但模型规模在某些情况下确实起作用。本研究为未来深度伪造检测框架的多模态推理整合提供了新思路，并为提升现实场景中的模型鲁棒性和可解释性提供了重要启示。

> Deepfake detection remains a critical challenge in the era of advanced generative models, particularly as synthetic media becomes more sophisticated. In this study, we explore the potential of state of the art multi-modal (reasoning) large language models (LLMs) for deepfake image detection such as (OpenAI O1/4o, Gemini thinking Flash 2, Deepseek Janus, Grok 3, llama 3.2, Qwen 2/2.5 VL, Mistral Pixtral, Claude 3.5/3.7 sonnet) . We benchmark 12 latest multi-modal LLMs against traditional deepfake detection methods across multiple datasets, including recently published real-world deepfake imagery. To enhance performance, we employ prompt tuning and conduct an in-depth analysis of the models' reasoning pathways to identify key contributing factors in their decision-making process. Our findings indicate that best multi-modal LLMs achieve competitive performance with promising generalization ability with zero shot, even surpass traditional deepfake detection pipelines in out-of-distribution datasets while the rest of the LLM families performs extremely disappointing with some worse than random guess. Furthermore, we found newer model version and reasoning capabilities does not contribute to performance in such niche tasks of deepfake detection while model size do help in some cases. This study highlights the potential of integrating multi-modal reasoning in future deepfake detection frameworks and provides insights into model interpretability for robustness in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2503.20084)