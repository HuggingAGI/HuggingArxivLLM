# 安全的隐秘空间：多语言环境下解析偏好调整的大型语言模型

发布时间：2025年04月03日

`LLM理论` `机器翻译`

> The Hidden Space of Safety: Understanding Preference-Tuned LLMs in Multilingual context

# 摘要

> 对齐调优使大型语言模型在推理、指令遵循和有害内容生成控制方面表现出色。然而，尽管这些模型被广泛应用，单语种偏见问题仍然存在，这引发了人们对跨语言对齐效果的担忧。当前的对齐方法主要集中在英语上，尚不清楚这些机制如何推广到多语言环境。为了解决这一问题，我们对LLMs在对齐前后的嵌入空间分布偏移进行了系统性分析，揭示了其对多种语言下模型行为的影响。我们利用对齐引发的安全空间分离作为量化工具，衡量对齐如何强制执行安全约束。我们的研究通过平衡毒性数据集和平行文本净化基准评估了七种LLMs，发现高资源语言与低资源语言在潜在表示空间中存在显著差异。这些发现强调了进行语言特定微调的必要性，以确保公平、可靠和稳健的多语言对齐。我们的见解为开发真正安全的多语言LLMs奠定了基础，突显了弥合小语种对齐差距的紧迫性。

> Alignment tuning has enabled large language models to excel in reasoning, instruction-following, and minimizing harmful generations. However, despite their widespread deployment, these models exhibit a monolingual bias, raising concerns about the effectiveness of alignment across languages. Current alignment methods predominantly focus on English, leaving it unclear how alignment mechanism generalize to multilingual settings. To address this, we conduct a systematic analysis of distributional shifts in the embedding space of LLMs before and after alignment, uncovering its impact on model behavior across diverse languages. We leverage the alignment-induced separation in safety space as a quantitative tool to measure how alignment enforces safety constraints. Our study evaluates seven LLMs using balanced toxicity datasets and parallel text-detoxification benchmarks, revealing substantial disparities in the latent representation space between high-resource and low-resource languages. These findings underscore the need for language-specific fine-tuning to ensure fair, reliable and robust multilingual alignment. Our insights provide a foundation for developing truly safe multilingual LLMs, emphasizing the urgency of addressing alignment gaps in underrepresented languages.

[Arxiv](https://arxiv.org/abs/2504.02708)