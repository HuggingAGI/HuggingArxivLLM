# SensorChat: 长期多模态传感器交互中的定性与定量问题解答

发布时间：2025年02月04日

`LLM应用

理由：这篇论文介绍了SensorChat，一个端到端的QA系统，专门设计用于长期传感器监测，能够处理多模态和高维数据。该系统利用大型语言模型（LLMs）进行问题分解和答案组装，并引入了一个显式的查询阶段以精确提取传感器数据中的信息。虽然涉及传感器数据的处理，但其核心在于利用LLMs进行自然语言交互和高级推理，因此应归类为LLM应用。` `物联网` `人机交互`

> SensorChat: Answering Qualitative and Quantitative Questions during Long-Term Multimodal Sensor Interactions

# 摘要

> # 摘要
与传感系统的自然语言交互对于让所有用户理解传感器数据及其对日常生活的影响至关重要。然而，现有的系统通常以问答（QA）方式运行，在处理传感器数据的持续时间和复杂性方面存在显著限制。在这项工作中，我们介绍了SensorChat，这是第一个为长期传感器监测设计的端到端QA系统，能够处理包括时间序列在内的多模态和高维数据。SensorChat在实际场景中有效回答了需要高级推理的定性问题和需要从传感器数据中得出准确响应的定量问题。为实现这一目标，SensorChat采用了一个创新的三阶段流程，包括问题分解、传感器数据查询和答案组装。第一阶段和第三阶段利用大型语言模型（LLMs）进行直观的人机交互，并指导传感器数据查询过程。与现有的多模态LLMs不同，SensorChat引入了一个显式的查询阶段，以精确地从长时间传感器数据中提取事实信息。我们实现了SensorChat，并展示了其在云服务器上实时交互的能力，同时也能在量化后完全在边缘平台上运行。全面的QA评估显示，SensorChat在定量问题上的答案准确率比最先进的系统高出26%。此外，一项有八名志愿者参与的用户研究突显了SensorChat在处理定性和开放式问题方面的有效性。

> Natural language interaction with sensing systems is crucial for enabling all users to comprehend sensor data and its impact on their everyday lives. However, existing systems, which typically operate in a Question Answering (QA) manner, are significantly limited in terms of the duration and complexity of sensor data they can handle. In this work, we introduce SensorChat, the first end-to-end QA system designed for long-term sensor monitoring with multimodal and high-dimensional data including time series. SensorChat effectively answers both qualitative (requiring high-level reasoning) and quantitative (requiring accurate responses derived from sensor data) questions in real-world scenarios. To achieve this, SensorChat uses an innovative three-stage pipeline that includes question decomposition, sensor data query, and answer assembly. The first and third stages leverage Large Language Models (LLMs) for intuitive human interactions and to guide the sensor data query process. Unlike existing multimodal LLMs, SensorChat incorporates an explicit query stage to precisely extract factual information from long-duration sensor data. We implement SensorChat and demonstrate its capability for real-time interactions on a cloud server while also being able to run entirely on edge platforms after quantization. Comprehensive QA evaluations show that SensorChat achieves up to 26% higher answer accuracy than state-of-the-art systems on quantitative questions. Additionally, a user study with eight volunteers highlights SensorChat's effectiveness in handling qualitative and open-ended questions.

[Arxiv](https://arxiv.org/abs/2502.02883)