# 仅此而已：利用意图区分与表情符号解析增强LLM的自我伤害检测能力

发布时间：2025年06月05日

`LLM应用` `心理健康` `社交媒体分析`

> Just a Scratch: Enhancing LLM Capabilities for Self-harm Detection through Intent Differentiation and Emoji Interpretation

# 摘要

> 社交媒体上的自我伤害检测对早期干预和心理健康支持至关重要，但由于这类表达的微妙性和上下文依赖性，仍具挑战性。识别自我伤害意图有助于预防自杀，但当前大型语言模型（LLMs）难以解读随意语言和表情符号中的隐含线索。本研究通过区分细微的语言-表情符号互动来提升LLMs对自我伤害的理解。我们提出了百年表情符号敏感性矩阵（CESM-100），这是一个精选的包含100个表情符号的集合，每个表情符号都附带了具体的自我伤害解释，并推出了自我伤害识别与意图提取及支持性表情符号敏感性（SHINES）数据集，提供了详细的自我伤害标签、随意提及（CMs）和严重意图（SIs）注释。我们的统一框架：a) 使用CESM-100丰富输入；b) 对LLMs进行微调以实现多任务学习：自我伤害检测（主要任务）和CM/SI跨度检测（辅助任务）；c) 为自我伤害预测生成可解释的理由。我们在三个最先进的LLMs（Llama 3、Mental-Alpaca 和 MentalLlama）上评估了该框架，在零样本、少样本和微调场景下进行测试。通过结合意图区分与上下文线索，我们的方法显著提升了LLMs在检测和解释任务中的性能，有效解决了自我伤害信号中的固有模糊性。SHINES数据集、CESM-100和代码库均可在以下链接公开获取：https://www.iitp.ac.in/~ai-nlp-ml/resources.html#SHINES。

> Self-harm detection on social media is critical for early intervention and mental health support, yet remains challenging due to the subtle, context-dependent nature of such expressions. Identifying self-harm intent aids suicide prevention by enabling timely responses, but current large language models (LLMs) struggle to interpret implicit cues in casual language and emojis. This work enhances LLMs' comprehension of self-harm by distinguishing intent through nuanced language-emoji interplay. We present the Centennial Emoji Sensitivity Matrix (CESM-100), a curated set of 100 emojis with contextual self-harm interpretations and the Self-Harm Identification aNd intent Extraction with Supportive emoji sensitivity (SHINES) dataset, offering detailed annotations for self-harm labels, casual mentions (CMs), and serious intents (SIs). Our unified framework: a) enriches inputs using CESM-100; b) fine-tunes LLMs for multi-task learning: self-harm detection (primary) and CM/SI span detection (auxiliary); c) generates explainable rationales for self-harm predictions. We evaluate the framework on three state-of-the-art LLMs-Llama 3, Mental-Alpaca, and MentalLlama, across zero-shot, few-shot, and fine-tuned scenarios. By coupling intent differentiation with contextual cues, our approach commendably enhances LLM performance in both detection and explanation tasks, effectively addressing the inherent ambiguity in self-harm signals. The SHINES dataset, CESM-100 and codebase are publicly available at: https://www.iitp.ac.in/~ai-nlp-ml/resources.html#SHINES .

[Arxiv](https://arxiv.org/abs/2506.05073)