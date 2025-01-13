# 面向目标导向的对话AI，基于LLMs增强的上下文ASR错误处理

发布时间：2025年01月10日

`LLM应用

理由：该论文摘要描述了一种结合大型语言模型（LLM）和对话状态上下文信息的方法，用于改进自动语音识别（ASR）系统在目标导向对话中的表现。这种方法利用了LLM的能力来处理词汇和句法的变化，并通过上下文信息对ASR假设进行排名。因此，该研究属于LLM在实际应用中的使用，即LLM应用。` `语音识别` `家庭装修`

> Contextual ASR Error Handling with LLMs Augmentation for Goal-Oriented Conversational AI

# 摘要

> 通用自动语音识别（ASR）系统在目标导向对话中表现不佳。现有ASR校正方法依赖用户历史数据或命名实体。我们提出了一种新方法，适用于无历史数据且语言灵活的任务，如词汇和句法变化。该方法结合大型语言模型和对话状态的上下文信息，通过词汇语义相似性和语音对应关系对ASR假设和上下文进行排名。在家庭装修和烹饪领域的真实用户测试中，该方法将校正的召回率和F1分别提升了34%和16%，同时保持精度和假阳性率。用户评分提高了0.8-1分（满分5分），且未因假阳性而降低。

> General-purpose automatic speech recognition (ASR) systems do not always perform well in goal-oriented dialogue. Existing ASR correction methods rely on prior user data or named entities. We extend correction to tasks that have no prior user data and exhibit linguistic flexibility such as lexical and syntactic variations. We propose a novel context augmentation with a large language model and a ranking strategy that incorporates contextual information from the dialogue states of a goal-oriented conversational AI and its tasks. Our method ranks (1) n-best ASR hypotheses by their lexical and semantic similarity with context and (2) context by phonetic correspondence with ASR hypotheses. Evaluated in home improvement and cooking domains with real-world users, our method improves recall and F1 of correction by 34% and 16%, respectively, while maintaining precision and false positive rate. Users rated .8-1 point (out of 5) higher when our correction method worked properly, with no decrease due to false positives.

[Arxiv](https://arxiv.org/abs/2501.06129)