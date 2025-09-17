# SitLLM：基于压力传感器数据的坐姿健康理解大型语言模型

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> SitLLM: Large Language Models for Sitting Posture Health Understanding via Pressure Sensor Data

# 摘要

> 不良坐姿是导致长期肌肉骨骼疾病与生理功能障碍的关键却常被忽视的诱因。现有坐姿监测系统虽已采用视觉、IMU或压力传感等模态，却普遍存在识别粒度粗糙的问题，且缺乏个性化反馈所需的语义表达能力。本文提出	extbf{SitLLM}——一个轻量级多模态框架，通过融合柔性压力传感与大型语言模型（LLMs），实现细粒度姿势理解与个性化健康导向的响应生成。SitLLM包含三个核心组件：（1）	extit{高斯鲁棒传感器嵌入模块}，将压力图分割为空间补丁并注入局部噪声扰动，以实现鲁棒特征提取；（2）	extit{提示驱动跨模态对齐模块}，借助预训练词汇嵌入，通过多头交叉注意力将传感器嵌入重编程至LLM的语义空间；（3）	extit{多上下文提示模块}，融合特征级、结构级、统计级及语义级上下文信息，以引导指令理解。

> Poor sitting posture is a critical yet often overlooked factor contributing to long-term musculoskeletal disorders and physiological dysfunctions. Existing sitting posture monitoring systems, although leveraging visual, IMU, or pressure-based modalities, often suffer from coarse-grained recognition and lack the semantic expressiveness necessary for personalized feedback. In this paper, we propose \textbf{SitLLM}, a lightweight multimodal framework that integrates flexible pressure sensing with large language models (LLMs) to enable fine-grained posture understanding and personalized health-oriented response generation. SitLLM comprises three key components: (1) a \textit{Gaussian-Robust Sensor Embedding Module} that partitions pressure maps into spatial patches and injects local noise perturbations for robust feature extraction; (2) a \textit{Prompt-Driven Cross-Modal Alignment Module} that reprograms sensor embeddings into the LLM's semantic space via multi-head cross-attention using the pre-trained vocabulary embeddings; and (3) a \textit{Multi-Context Prompt Module} that fuses feature-level, structure-level, statistical-level, and semantic-level contextual information to guide instruction comprehension.

[Arxiv](https://arxiv.org/abs/2509.12994)