# GuideLLM: 探索 LLM 引导的对话及其在自传式访谈中的应用

发布时间：2025年02月10日

`LLM应用` `对话系统` `人工智能`

> GuideLLM: Exploring LLM-Guided Conversation with Applications in Autobiography Interviewing

# 摘要

> 大型语言模型（LLMs）在遵循指令和回答问题等人类引导的对话中表现出色，但其主导对话方向并把控目标的潜力尚未得到充分挖掘。本研究将LLM引导对话归纳为三个核心要素：目标导航、上下文管理和共情参与，并提出GuideLLM作为实现方案。我们构建了一个用于评估LLM引导对话的访谈环境，涵盖多个主题以进行全面评估，每个聊天机器人的评估过程中产生了约1,400轮对话、18.4万个令牌以及超过200个提及的事件。我们从访谈质量和自传生成质量两个角度，将GuideLLM与GPT-4o和Llama-3-70b-Instruct等6个先进LLMs进行了对比。在自动评估中，我们从多个自传中提取用户代理，并利用LLM作为评估器对LLM的行为进行评分。我们还开展了一项包含45名人类参与者的实验，让他们与GuideLLM和基线模型进行对话，并收集了参与者对对话质量及自传质量的反馈、偏好和评分。实验结果表明，GuideLLM在自动评估中显著优于基线模型，并在人工评分中保持了一致的领先表现。

> Although Large Language Models (LLMs) succeed in human-guided conversations such as instruction following and question answering, the potential of LLM-guided conversations-where LLMs direct the discourse and steer the conversation's objectives-remains under-explored. In this study, we first characterize LLM-guided conversation into three fundamental components: (i) Goal Navigation; (ii) Context Management; (iii) Empathetic Engagement, and propose GuideLLM as an installation. We then implement an interviewing environment for the evaluation of LLM-guided conversation. Specifically, various topics are involved in this environment for comprehensive interviewing evaluation, resulting in around 1.4k turns of utterances, 184k tokens, and over 200 events mentioned during the interviewing for each chatbot evaluation. We compare GuideLLM with 6 state-of-the-art LLMs such as GPT-4o and Llama-3-70b-Instruct, from the perspective of interviewing quality, and autobiography generation quality. For automatic evaluation, we derive user proxies from multiple autobiographies and employ LLM-as-a-judge to score LLM behaviors. We further conduct a human-involved experiment by employing 45 human participants to chat with GuideLLM and baselines. We then collect human feedback, preferences, and ratings regarding the qualities of conversation and autobiography. Experimental results indicate that GuideLLM significantly outperforms baseline LLMs in automatic evaluation and achieves consistent leading performances in human ratings.

[Arxiv](https://arxiv.org/abs/2502.06494)