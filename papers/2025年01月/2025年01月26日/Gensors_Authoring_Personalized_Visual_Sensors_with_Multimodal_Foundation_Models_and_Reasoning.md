# Gensors: 基于多模态基础模型与推理的个性化视觉传感器创作

发布时间：2025年01月26日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在个性化AI传感器中的应用。论文介绍了Gensors系统，该系统利用MLLMs的推理能力来帮助用户定义和调试定制传感器。虽然涉及到了多模态和推理能力，但核心内容集中在如何应用这些技术来解决实际问题，因此归类为LLM应用。` `智能家居` `用户交互`

> Gensors: Authoring Personalized Visual Sensors with Multimodal Foundation Models and Reasoning

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）凭借其广泛的世界知识和推理能力，为终端用户提供了一个独特的机会，使他们能够创建能够推理复杂情况的个性化AI传感器。用户可以用自然语言描述所需的传感任务（例如，“如果我的小孩在捣乱就发出警报”），MLLM会在几秒钟内分析摄像头画面并做出响应。在一项初步研究中，我们发现用户对定义自己的传感器有很大的价值，但仅通过提示难以清晰表达其独特的个人需求并调试传感器。为了解决这些挑战，我们开发了Gensors，这是一个系统，使用户能够定义由MLLMs推理能力支持的定制传感器。Gensors 1）通过自动生成和手动创建的传感器标准帮助用户引出需求，2）通过允许用户并行隔离和测试单个标准来促进调试，3）根据用户提供的图像建议额外的标准，4）提出测试用例，帮助用户“压力测试”传感器在可能未预见的情况下的表现。在一项用户研究中，参与者报告称，使用Gensors定义传感器时，他们的控制感、理解力和沟通便利性显著提高。除了解决模型限制外，Gensors还支持用户通过基于标准的推理进行调试、引出需求并向传感器表达独特的个人需求；它还通过暴露被忽视的标准和揭示未预见的故障模式，帮助发现用户的“盲点”。最后，我们讨论了MLLMs的独特特性——如幻觉和不一致的响应——如何影响传感器创建过程。这些发现有助于设计未来由日常用户直观且可定制的智能传感系统。

> Multimodal large language models (MLLMs), with their expansive world knowledge and reasoning capabilities, present a unique opportunity for end-users to create personalized AI sensors capable of reasoning about complex situations. A user could describe a desired sensing task in natural language (e.g., "alert if my toddler is getting into mischief"), with the MLLM analyzing the camera feed and responding within seconds. In a formative study, we found that users saw substantial value in defining their own sensors, yet struggled to articulate their unique personal requirements and debug the sensors through prompting alone. To address these challenges, we developed Gensors, a system that empowers users to define customized sensors supported by the reasoning capabilities of MLLMs. Gensors 1) assists users in eliciting requirements through both automatically-generated and manually created sensor criteria, 2) facilitates debugging by allowing users to isolate and test individual criteria in parallel, 3) suggests additional criteria based on user-provided images, and 4) proposes test cases to help users "stress test" sensors on potentially unforeseen scenarios. In a user study, participants reported significantly greater sense of control, understanding, and ease of communication when defining sensors using Gensors. Beyond addressing model limitations, Gensors supported users in debugging, eliciting requirements, and expressing unique personal requirements to the sensor through criteria-based reasoning; it also helped uncover users' "blind spots" by exposing overlooked criteria and revealing unanticipated failure modes. Finally, we discuss how unique characteristics of MLLMs--such as hallucinations and inconsistent responses--can impact the sensor-creation process. These findings contribute to the design of future intelligent sensing systems that are intuitive and customizable by everyday users.

[Arxiv](https://arxiv.org/abs/2501.15727)