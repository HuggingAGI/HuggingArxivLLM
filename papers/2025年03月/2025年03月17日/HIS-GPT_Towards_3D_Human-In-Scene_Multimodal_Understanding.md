# HIS-GPT：探索三维人体场景的多模态理解能力

发布时间：2025年03月17日

`Agent` `人工智能` `三维场景分析`

> HIS-GPT: Towards 3D Human-In-Scene Multimodal Understanding

# 摘要

> 我们提出了一项新任务——场景中人物问答（HIS-QA），用于评估具身智能体对场景中人物的理解能力。给定一个三维场景中的人体运动，HIS-QA要求智能体理解人物的状态和行为，推理其周围环境，并在场景中回答与人物相关的问题。为了支持这一新任务，我们推出了HIS-Bench，这是一个多模态基准测试，系统地评估了从基础感知到常识推理和规划的广泛范围内对HIS的理解。我们在HIS-Bench上对各种视觉-语言模型的评估揭示了它们在处理HIS-QA任务方面存在显著局限性。为此，我们提出了HIS-GPT，首个专注于HIS理解的基础模型。HIS-GPT将三维场景上下文和人体运动动力学整合到大型语言模型中，同时引入了专门机制来捕捉人与场景的交互。大量实验表明，HIS-GPT在HIS-QA任务上达到了新的技术前沿。我们希望这项工作能够激发未来对三维场景中人类行为分析的研究，推动具身AI和世界模型的发展。

> We propose a new task to benchmark human-in-scene understanding for embodied agents: Human-In-Scene Question Answering (HIS-QA). Given a human motion within a 3D scene, HIS-QA requires the agent to comprehend human states and behaviors, reason about its surrounding environment, and answer human-related questions within the scene. To support this new task, we present HIS-Bench, a multimodal benchmark that systematically evaluates HIS understanding across a broad spectrum, from basic perception to commonsense reasoning and planning. Our evaluation of various vision-language models on HIS-Bench reveals significant limitations in their ability to handle HIS-QA tasks. To this end, we propose HIS-GPT, the first foundation model for HIS understanding. HIS-GPT integrates 3D scene context and human motion dynamics into large language models while incorporating specialized mechanisms to capture human-scene interactions. Extensive experiments demonstrate that HIS-GPT sets a new state-of-the-art on HIS-QA tasks. We hope this work inspires future research on human behavior analysis in 3D scenes, advancing embodied AI and world models.

[Arxiv](https://arxiv.org/abs/2503.12955)