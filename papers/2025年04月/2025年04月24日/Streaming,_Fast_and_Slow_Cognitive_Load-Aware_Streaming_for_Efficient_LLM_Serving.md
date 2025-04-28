# 流式传输，快与慢之道：认知负载感知流式传输技术，打造高效的大语言模型服务。

发布时间：2025年04月24日

`LLM应用` `云计算` `对话系统`

> Streaming, Fast and Slow: Cognitive Load-Aware Streaming for Efficient LLM Serving

# 摘要

> 基于大型语言模型（LLMs）的生成式对话界面通常逐个生成输出内容，速度由计算预算决定，但常常忽略了人类的实际阅读速度和内容的认知负荷。这种不匹配常导致计算资源的低效使用。例如，在基于云的服务中，输出速度过快超出用户阅读能力，不仅浪费资源，还可能在高峰时段导致其他用户延迟。为解决此问题，我们提出了一种自适应流式方法，可根据推断出的认知负荷实时动态调整LLM输出速度。我们的方法通过估计流式内容的认知负荷，在复杂或信息丰富的段落中减缓流速，从而释放资源供其他用户使用。统计分析和众包用户研究表明，我们的方法可将计算消耗降低高达16.8%，在提升系统效率的同时不牺牲用户体验，为基于云的对话式AI界面提供了一个实用的资源管理框架。

> Generative conversational interfaces powered by large language models (LLMs) typically stream output token-by-token at a rate determined by computational budget, often neglecting actual human reading speeds and the cognitive load associated with the content. This mismatch frequently leads to inefficient use of computational resources. For example, in cloud-based services, streaming content faster than users can read appears unnecessary, resulting in wasted computational resources and potential delays for other users, particularly during peak usage periods. To address this issue, we propose an adaptive streaming method that dynamically adjusts the pacing of LLM streaming output in real-time based on inferred cognitive load. Our approach estimates the cognitive load associated with streaming content and strategically slows down the stream during complex or information-rich segments, thereby freeing computational resources for other users. Our statistical analysis of computational savings, combined with crowdsourced user studies, provides insights into the trade-offs between service efficiency and user satisfaction, demonstrating that our method can significantly reduce computational consumption up to 16.8\%. This context-aware computational resource management strategy presents a practical framework for enhancing system efficiency in cloud-based conversational AI interfaces without compromising user experience.

[Arxiv](https://arxiv.org/abs/2504.17999)