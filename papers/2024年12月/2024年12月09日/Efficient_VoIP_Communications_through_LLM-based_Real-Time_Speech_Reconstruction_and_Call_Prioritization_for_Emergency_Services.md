# 基于LLM的实时语音重建与紧急服务呼叫优先级排序，助力高效VoIP通信

发布时间：2024年12月09日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决紧急通信系统中的问题，包括语音重建、上下文填补和呼叫优先级处理。这些应用场景直接涉及LLM在实际问题中的使用，因此应归类为“LLM应用”。虽然论文中提到了检索增强生成（RAG），但RAG在这里是作为LLM应用的一部分，而不是论文的核心主题。` `紧急通信` `语音处理`

> Efficient VoIP Communications through LLM-based Real-Time Speech Reconstruction and Call Prioritization for Emergency Services

# 摘要

> # 摘要
紧急通信系统常因数据包丢失、带宽限制、信号质量差、延迟和VoIP系统中的抖动而中断，导致实时服务质量下降。受害者因恐慌、语言障碍和背景噪音难以传达关键信息，进一步增加了调度员准确评估情况的难度。紧急中心的人员短缺也加剧了协调和援助的延迟。本文提出利用大型语言模型（LLMs）来解决这些问题，通过重建不完整语音、填补上下文空白并根据严重程度优先处理呼叫。该系统结合实时转录与检索增强生成（RAG）生成上下文响应，并利用Twilio和AssemblyAI API实现无缝集成。评估结果显示高精度、良好的BLEU和ROUGE分数，且与真实需求高度契合，证明了该模型在优化紧急响应流程和有效优先处理关键案例方面的潜力。

> Emergency communication systems face disruptions due to packet loss, bandwidth constraints, poor signal quality, delays, and jitter in VoIP systems, leading to degraded real-time service quality. Victims in distress often struggle to convey critical information due to panic, speech disorders, and background noise, further complicating dispatchers' ability to assess situations accurately. Staffing shortages in emergency centers exacerbate delays in coordination and assistance. This paper proposes leveraging Large Language Models (LLMs) to address these challenges by reconstructing incomplete speech, filling contextual gaps, and prioritizing calls based on severity. The system integrates real-time transcription with Retrieval-Augmented Generation (RAG) to generate contextual responses, using Twilio and AssemblyAI APIs for seamless implementation. Evaluation shows high precision, favorable BLEU and ROUGE scores, and alignment with real-world needs, demonstrating the model's potential to optimize emergency response workflows and prioritize critical cases effectively.

[Arxiv](https://arxiv.org/abs/2412.16176)