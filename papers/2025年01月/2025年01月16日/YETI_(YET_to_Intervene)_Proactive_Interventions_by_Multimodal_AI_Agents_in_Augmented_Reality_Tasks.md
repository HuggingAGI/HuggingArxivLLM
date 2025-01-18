# YETI（尚未干预）：多模态AI代理在增强现实任务中的主动干预

发布时间：2025年01月16日

`Agent

理由：这篇论文主要讨论的是多模态AI代理（YETI代理）的设计和应用，特别是如何通过主动干预来帮助用户完成任务。论文的核心内容围绕AI代理的行为模式、决策机制以及与用户的交互方式展开，这些都是典型的Agent研究范畴。因此，这篇论文应归类为Agent。` `增强现实` `人机交互`

> YETI (YET to Intervene) Proactive Interventions by Multimodal AI Agents in Augmented Reality Tasks

# 摘要

> # 摘要
多模态AI代理能够交互协作地帮助人类用户解决日常任务。AR头戴设备通过提供以自我为中心的多模态（音频和视频）观察能力，显著提升了用户解决日常程序性任务的体验。这种AR能力使AI代理能够“看到”和“听到”用户的行动，从而与人类用户的多模态能力产生关联。现有的AI代理（如LLMs和VLMs）通常是被动的，无法在未收到用户提示前采取行动。而主动性的AI代理则能帮助用户检测并纠正任务中的错误，或在用户正确完成任务时给予鼓励，甚至与用户进行对话，类似于人类的教学或协助。我们提出的YETI多模态代理专注于研究何时需要主动干预，使其能够在与用户的对话中适时介入，帮助纠正任务错误（如使用AR烹饪）。YETI代理通过连续视频帧的结构相似性（SSIM）学习场景理解信号，并定义了对齐信号，以判断用户行动是否与预期一致。这些信号帮助AI代理决定何时主动干预。我们在HoloAssist多模态基准中测试了主动干预的效果，该基准用于指导用户完成程序性任务。

> Multimodal AI Agents are AI models that have the capability of interactively and cooperatively assisting human users to solve day-to-day tasks. Augmented Reality (AR) head worn devices can uniquely improve the user experience of solving procedural day-to-day tasks by providing egocentric multimodal (audio and video) observational capabilities to AI Agents. Such AR capabilities can help AI Agents see and listen to actions that users take which can relate to multimodal capabilities of human users. Existing AI Agents, either Large Language Models (LLMs) or Multimodal Vision-Language Models (VLMs) are reactive in nature, which means that models cannot take an action without reading or listening to the human user's prompts. Proactivity of AI Agents on the other hand can help the human user detect and correct any mistakes in agent observed tasks, encourage users when they do tasks correctly or simply engage in conversation with the user - akin to a human teaching or assisting a user. Our proposed YET to Intervene (YETI) multimodal agent focuses on the research question of identifying circumstances that may require the agent to intervene proactively. This allows the agent to understand when it can intervene in a conversation with human users that can help the user correct mistakes on tasks, like cooking, using AR. Our YETI Agent learns scene understanding signals based on interpretable notions of Structural Similarity (SSIM) on consecutive video frames. We also define the alignment signal which the AI Agent can learn to identify if the video frames corresponding to the user's actions on the task are consistent with expected actions. These signals are used by our AI Agent to determine when it should proactively intervene. We compare our results on the instances of proactive intervention in the HoloAssist multimodal benchmark for an expert agent guiding a user to complete procedural tasks.

[Arxiv](https://arxiv.org/abs/2501.09355)