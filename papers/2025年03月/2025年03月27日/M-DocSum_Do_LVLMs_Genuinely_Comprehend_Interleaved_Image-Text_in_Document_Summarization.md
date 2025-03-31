# M-DocSum：大型视觉语言模型是否真正理解文档摘要中的图文交织内容？

发布时间：2025年03月27日

`LLM应用` `文档理解` `多模态`

> M-DocSum: Do LVLMs Genuinely Comprehend Interleaved Image-Text in Document Summarization?

# 摘要

> 我们探讨了一个在大型视觉语言模型 (LVLMs) 中关键但未被充分探索的问题：这些模型是否真正理解文档中的交错图像-文本内容？现有的文档理解基准通常使用问答格式来评估 LVLMs，这种格式信息稀疏，难以保证对长距离依赖关系的覆盖。为了解决这一问题，我们引入了一个新颖且具有挑战性的多模态文档摘要基准 (M-DocSum-Bench)，其中包含 500 篇高质量的 arXiv 论文，以及与人类偏好一致的交错多模态摘要。M-DocSum-Bench 是一个基于参考的生成任务，需要根据提供的参考图像生成交错的图像-文本摘要，从而同时评估在复杂多模态文档场景中对理解、推理、定位和总结能力。为了支持这一基准，我们开发了一个自动化框架来构建摘要，并提出了一种称为 M-DocEval 的细粒度评估方法。此外，我们进一步开发了一个强大的摘要基线，即 M-DocSum-7B，通过使用多样化的指令和偏好数据进行渐进的两阶段训练。在我们的 M-DocSum-Bench 上的广泛实验结果表明，领先的 LVLMs 难以在长且交错的上下文中保持连贯性并准确整合信息，通常表现出对相似图像的混淆和缺乏鲁棒性。值得注意的是，与更大的闭源模型（包括 GPT-4o、Gemini Pro、Claude-3.5-Sonnet 和 Qwen2.5-VL-72B 等）相比，M-DocSum-7B 实现了最先进的性能，这表明 LVLMs 在改进交错图像-文本理解方面具有潜力。代码、数据和模型可在 https://github.com/stepfun-ai/M-DocSum-Bench 获取。

> We investigate a critical yet under-explored question in Large Vision-Language Models (LVLMs): Do LVLMs genuinely comprehend interleaved image-text in the document? Existing document understanding benchmarks often assess LVLMs using question-answer formats, which are information-sparse and difficult to guarantee the coverage of long-range dependencies. To address this issue, we introduce a novel and challenging Multimodal Document Summarization Benchmark (M-DocSum-Bench), which comprises 500 high-quality arXiv papers, along with interleaved multimodal summaries aligned with human preferences. M-DocSum-Bench is a reference-based generation task and necessitates the generation of interleaved image-text summaries using provided reference images, thereby simultaneously evaluating capabilities in understanding, reasoning, localization, and summarization within complex multimodal document scenarios. To facilitate this benchmark, we develop an automated framework to construct summaries and propose a fine-grained evaluation method called M-DocEval. Moreover, we further develop a robust summarization baseline, i.e., M-DocSum-7B, by progressive two-stage training with diverse instruction and preference data. The extensive results on our M-DocSum-Bench reveal that the leading LVLMs struggle to maintain coherence and accurately integrate information within long and interleaved contexts, often exhibiting confusion between similar images and a lack of robustness. Notably, M-DocSum-7B achieves state-of-the-art performance compared to larger and closed-source models (including GPT-4o, Gemini Pro, Claude-3.5-Sonnet and Qwen2.5-VL-72B, etc.), demonstrating the potential of LVLMs for improved interleaved image-text understanding. The code, data, and models are available at https://github.com/stepfun-ai/M-DocSum-Bench.

[Arxiv](https://arxiv.org/abs/2503.21839)