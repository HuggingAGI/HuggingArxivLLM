# AI能否追踪并解释AI生成的图像和文本的来源？这项研究旨在探索AI在追踪和解释AI生成内容起源方面的潜力。

发布时间：2025年04月05日

`LLM应用` `AI检测`

> Could AI Trace and Explain the Origins of AI-Generated Images and Text?

# 摘要

> AI生成内容在现实世界中越来越普遍，引发了一系列严重的伦理和社会关切。例如，恶意行为者可能利用大型多模态模型生成违反伦理或法律标准的图像，而论文审稿人可能滥用大型语言模型生成缺乏真实智力投入的评论。尽管先前的研究在检测AI生成的图像和文本，并偶尔追溯其来源模型方面有所探索，但缺乏系统性和细致的比较研究。重要维度，如AI生成的图像与文本、完全与部分生成的图像、以及一般与恶意使用案例，仍待深入探索。此外，像GPT-4o这样的AI系统是否能解释为何某些伪造内容归因于特定生成模型，仍是一个开放问题，现有基准未解决这一问题。为填补这一空白，我们引入了AI-FAKER，一个涵盖多个LLMs和LMMs的综合多模态数据集，包含超过28万样本，涵盖AI生成图像和文本的一般和恶意使用案例。我们的实验揭示了两个关键发现：(i) AI创作检测不仅依赖于生成的输出，还取决于模型最初的训练意图；(ii) GPT-4o在分析OpenAI自家模型（如DALL-E和GPT-4o本身）生成的内容时，提供高度一致但不够具体的解释。

> AI-generated content is becoming increasingly prevalent in the real world, leading to serious ethical and societal concerns. For instance, adversaries might exploit large multimodal models (LMMs) to create images that violate ethical or legal standards, while paper reviewers may misuse large language models (LLMs) to generate reviews without genuine intellectual effort. While prior work has explored detecting AI-generated images and texts, and occasionally tracing their source models, there is a lack of a systematic and fine-grained comparative study. Important dimensions--such as AI-generated images vs. text, fully vs. partially AI-generated images, and general vs. malicious use cases--remain underexplored. Furthermore, whether AI systems like GPT-4o can explain why certain forged content is attributed to specific generative models is still an open question, with no existing benchmark addressing this. To fill this gap, we introduce AI-FAKER, a comprehensive multimodal dataset with over 280,000 samples spanning multiple LLMs and LMMs, covering both general and malicious use cases for AI-generated images and texts. Our experiments reveal two key findings: (i) AI authorship detection depends not only on the generated output but also on the model's original training intent; and (ii) GPT-4o provides highly consistent but less specific explanations when analyzing content produced by OpenAI's own models, such as DALL-E and GPT-4o itself.

[Arxiv](https://arxiv.org/abs/2504.04279)