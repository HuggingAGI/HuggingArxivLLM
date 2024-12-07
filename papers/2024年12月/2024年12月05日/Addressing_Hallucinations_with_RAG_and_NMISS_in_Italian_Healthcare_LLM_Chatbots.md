# 处理意大利医疗保健 LLM 聊天机器人中的 RAG 和 NMISS 所导致的幻觉现象

发布时间：2024年12月05日

`LLM应用`

> Addressing Hallucinations with RAG and NMISS in Italian Healthcare LLM Chatbots

# 摘要

> 我将检测与缓解技术相结合，以应对大型语言模型（LLMs）中的幻觉现象。在问答检索增强生成（RAG）框架中实现缓解，同时引入负缺失信息评分系统（NMISS）进行检测，该系统会考量响应中的上下文相关性。RAG 借助外部数据为答案提供依据从而缓解幻觉，而 NMISS 则通过甄别传统指标误将上下文准确的响应判定为幻觉的情况来优化评估。我以意大利健康新闻文章为背景来评估 LLM 性能。结果显示，Gemma2 和 GPT-4 的表现优于其他模型，GPT-4 生成的答案与参考响应高度吻合。中层模型，如 Llama2、Llama3 和 Mistral 因 NMISS 而获益显著，凸显了它们提供更丰富上下文信息的能力。这种综合方法为降低和更精准评估 LLMs 中的幻觉提供了新视角，在现实世界的医疗保健任务及其他领域均有应用。

> I combine detection and mitigation techniques to addresses hallucinations in Large Language Models (LLMs). Mitigation is achieved in a question-answering Retrieval-Augmented Generation (RAG) framework while detection is obtained by introducing the Negative Missing Information Scoring System (NMISS), which accounts for contextual relevance in responses. While RAG mitigates hallucinations by grounding answers in external data, NMISS refines the evaluation by identifying cases where traditional metrics incorrectly flag contextually accurate responses as hallucinations. I use Italian health news articles as context to evaluate LLM performance. Results show that Gemma2 and GPT-4 outperform the other models, with GPT-4 producing answers closely aligned with reference responses. Mid-tier models, such as Llama2, Llama3, and Mistral benefit significantly from NMISS, highlighting their ability to provide richer contextual information. This combined approach offers new insights into the reduction and more accurate assessment of hallucinations in LLMs, with applications in real-world healthcare tasks and other domains.

[Arxiv](https://arxiv.org/abs/2412.04235)