# 基于通话录音数据集克隆电话销售对话式语音AI智能体

发布时间：2025年09月05日

`Agent` `零售与电商`

> Cloning a Conversational Voice AI Agent from Call\,Recording Datasets for Telesales

# 摘要

> 语言与语音建模的最新突破，让构建能实时理解并生成人类对话的自主语音助手成为现实。这类系统如今在客户服务、医疗保健等领域应用日益广泛，能自动处理重复任务、削减运营成本，并提供全天候不间断支持。本文提出了一种通用方法，可从通话录音语料库克隆出对话式语音AI代理。尽管文中案例研究以电话销售数据为例演示该方法，但其核心流程可推广至所有具备通话记录的领域。该系统能通过电话倾听客户需求，用合成语音回应，并遵循从顶尖人类客服那里习得的结构化话术。我们详细阐述了构建该代理所涉及的领域选择、知识提取与提示工程，同时将自动语音识别、基于大语言模型的对话管理器及文本转语音合成功整合进流式推理管道。我们从介绍、产品介绍、销售推动力、异议处理及成交等22个维度，将克隆代理与人类代理进行对比评估。盲测结果显示，AI代理在通话常规环节的表现已接近人类，但在说服力与异议处理上仍有不足。我们针对这些短板优化了提示词设计。最后，本文总结了设计经验与未来研究方向，包括大规模模拟和自动化评估等方向。

> Recent advances in language and speech modelling have made it possible to build autonomous voice assistants that understand and generate human dialogue in real time. These systems are increasingly being deployed in domains such as customer service and healthcare care, where they can automate repetitive tasks, reduce operational costs, and provide constant support around the clock. In this paper, we present a general methodology for cloning a conversational voice AI agent from a corpus of call recordings. Although the case study described in this paper uses telesales data to illustrate the approach, the underlying process generalizes to any domain where call transcripts are available. Our system listens to customers over the telephone, responds with a synthetic voice, and follows a structured playbook learned from top performing human agents. We describe the domain selection, knowledge extraction, and prompt engineering used to construct the agent, integrating automatic speech recognition, a large language model based dialogue manager, and text to speech synthesis into a streaming inference pipeline. The cloned agent is evaluated against human agents on a rubric of 22 criteria covering introduction, product communication, sales drive, objection handling, and closing. Blind tests show that the AI agent approaches human performance in routine aspects of the call while underperforming in persuasion and objection handling. We analyze these shortcomings and refine the prompt accordingly. The paper concludes with design lessons and avenues for future research, including large scale simulation and automated evaluation.

[Arxiv](https://arxiv.org/abs/2509.04871)