# 协作式实例导航：借助代理的自对话以减少用户输入

发布时间：2024年12月02日

`Agent` `具身实例目标导航`

> Collaborative Instance Navigation: Leveraging Agent Self-Dialogue to Minimize User Input

# 摘要

> 现有的自然语言驱动的具身实例目标导航任务，都假设人类用户在导航前能给出完整且细致的实例描述，然而在现实中这很难实现，因为人类的指令往往简短又模糊。为了填补这一空缺，我们提出了一个新任务——协作实例导航（CoIN），它在导航过程中有着动态的代理-人类交互，能在自然、无模板、开放式的对话里积极解决有关目标实例的不确定性。为应对 CoIN 任务，我们提出了一种新方法——具有不确定性意识的代理-用户交互（AIUTA），借助了视觉语言模型（VLMs）的感知能力和大型语言模型（LLMs）的能力。首先，在进行对象检测时，自我提问模型会开启自我对话来获取完整准确的观察描述，同时新的不确定性估计技术能降低 VLM 感知的不准确性。接着，交互触发模块决定是否向用户提问、继续还是停止导航，以最大程度减少用户输入。为了评估，我们引入了 CoIN-Bench，这是一个同时支持真实和模拟人类的基准。AIUTA 在实例导航方面与前沿方法相比表现出色，在处理用户输入方面展现出极大的灵活性。

> Existing embodied instance goal navigation tasks, driven by natural language, assume human users to provide complete and nuanced instance descriptions prior to the navigation, which can be impractical in the real world as human instructions might be brief and ambiguous. To bridge this gap, we propose a new task, Collaborative Instance Navigation (CoIN), with dynamic agent-human interaction during navigation to actively resolve uncertainties about the target instance in natural, template-free, open-ended dialogues. To address CoIN, we propose a novel method, Agent-user Interaction with UncerTainty Awareness (AIUTA), leveraging the perception capability of Vision Language Models (VLMs) and the capability of Large Language Models (LLMs). First, upon object detection, a Self-Questioner model initiates a self-dialogue to obtain a complete and accurate observation description, while a novel uncertainty estimation technique mitigates inaccurate VLM perception. Then, an Interaction Trigger module determines whether to ask a question to the user, continue or halt navigation, minimizing user input. For evaluation, we introduce CoIN-Bench, a benchmark supporting both real and simulated humans. AIUTA achieves competitive performance in instance navigation against state-of-the-art methods, demonstrating great flexibility in handling user inputs.

[Arxiv](https://arxiv.org/abs/2412.01250)