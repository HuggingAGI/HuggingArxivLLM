# 从 RAG 到 Agentic：LLM 代理在伊斯兰医学中的响应验证与应用探索

发布时间：2025年06月18日

`LLM应用` `人工智能`

> From RAG to Agentic: Validating Islamic-Medicine Responses with LLM Agents

# 摘要

> 历史悠久的伊斯兰医学典籍如《医典》和《先知医学》蕴含了丰富的预防性护理、营养学和整体疗法知识，但这些珍贵资源至今仍未得到广泛应用，尤其在现代AI系统中尚未充分发挥其价值。现有的语言模型基准测试大多局限于事实记忆或用户偏好，未能在大规模验证文化背景深厚的医疗指导方面提供支持。为此，我们提出了一个统一的评估框架Tibbe-AG，将30个精心挑选的先知医学问题与经过人工验证的治疗方法相结合，并对比了三种大型语言模型（LLaMA-3, Mistral-7B, Qwen2-7B）在直接生成、检索增强生成和科学自我批评过滤器三种配置下的表现。每个答案随后由一个作为代理法官的二级LLM进行评估，最终获得一个3C3H质量评分。通过引入检索功能，事实准确性提升了13%，而代理提示则通过更深入的机制洞察和安全考量，进一步提高了10%的效果。我们的研究结果表明，将古典伊斯兰医学文本与检索功能和自我评估相结合，能够实现可靠且文化敏感的医疗问答系统。

> Centuries-old Islamic medical texts like Avicenna's Canon of Medicine and the Prophetic Tibb-e-Nabawi encode a wealth of preventive care, nutrition, and holistic therapies, yet remain inaccessible to many and underutilized in modern AI systems. Existing language-model benchmarks focus narrowly on factual recall or user preference, leaving a gap in validating culturally grounded medical guidance at scale. We propose a unified evaluation pipeline, Tibbe-AG, that aligns 30 carefully curated Prophetic-medicine questions with human-verified remedies and compares three LLMs (LLaMA-3, Mistral-7B, Qwen2-7B) under three configurations: direct generation, retrieval-augmented generation, and a scientific self-critique filter. Each answer is then assessed by a secondary LLM serving as an agentic judge, yielding a single 3C3H quality score. Retrieval improves factual accuracy by 13%, while the agentic prompt adds another 10% improvement through deeper mechanistic insight and safety considerations. Our results demonstrate that blending classical Islamic texts with retrieval and self-evaluation enables reliable, culturally sensitive medical question-answering.

[Arxiv](https://arxiv.org/abs/2506.15911)