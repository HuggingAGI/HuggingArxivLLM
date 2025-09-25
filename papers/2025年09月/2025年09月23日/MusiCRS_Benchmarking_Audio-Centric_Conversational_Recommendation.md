# MusiCRS：构建以音频为中心的对话推荐基准

发布时间：2025年09月23日

`LLM应用` `媒体与娱乐`

> MusiCRS: Benchmarking Audio-Centric Conversational Recommendation

# 摘要

> 在大型语言模型（LLMs）的推动下，对话推荐发展迅猛，但音乐领域仍是一块难啃的骨头——有效的推荐需要对音频内容进行深度推理，这远非文本或元数据所能涵盖。为此，我们推出了MusiCRS——首个以音频为核心的对话推荐基准，它巧妙地将Reddit上的真实用户对话与对应的音轨关联起来。MusiCRS包含477段高质量对话，覆盖古典、嘻哈、电子、金属、流行、独立、爵士等多种流派，涉及3589个独特音乐实体，并通过YouTube链接提供音频支持。MusiCRS支持三种输入模态配置的评估：仅音频、仅查询、音频+查询（多模态），可对音频LLM、检索模型及传统方法展开系统性对比。实验结果显示，现有系统过度依赖文本信号，在复杂的音频推理上表现欠佳。这揭示了跨模态知识融合的根本局限：模型虽擅长对话语义理解，却难以将抽象的音乐概念有效关联到实际音频内容中。为推动该领域发展，我们公开了MusiCRS数据集（https://huggingface.co/datasets/rohan2810/MusiCRS）、评估代码（https://github.com/rohan2810/musiCRS）及完整基线。

> Conversational recommendation has advanced rapidly with large language models (LLMs), yet music remains a uniquely challenging domain where effective recommendations require reasoning over audio content beyond what text or metadata can capture. We present MusiCRS, the first benchmark for audio-centric conversational recommendation that links authentic user conversations from Reddit with corresponding audio tracks. MusiCRS contains 477 high-quality conversations spanning diverse genres (classical, hip-hop, electronic, metal, pop, indie, jazz) with 3,589 unique musical entities and audio grounding via YouTube links. MusiCRS enables evaluation across three input modality configurations: audio-only, query-only, and audio+query (multimodal), allowing systematic comparison of audio-LLMs, retrieval models, and traditional approaches. Our experiments reveal that current systems rely heavily on textual signals and struggle with nuanced audio reasoning. This exposes fundamental limitations in cross-modal knowledge integration where models excel at dialogue semantics but cannot effectively ground abstract musical concepts in actual audio content. To facilitate progress, we release the MusiCRS dataset (https://huggingface.co/datasets/rohan2810/MusiCRS), evaluation code (https://github.com/rohan2810/musiCRS), and comprehensive baselines.

[Arxiv](https://arxiv.org/abs/2509.19469)