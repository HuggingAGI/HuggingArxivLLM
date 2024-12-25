# 3DGraphLLM：融合语义图与大型语言模型以实现 3D 场景理解

发布时间：2024年12月24日

`LLM应用` `机器人` `3D 场景`

> 3DGraphLLM: Combining Semantic Graphs and Large Language Models for 3D Scene Understanding

# 摘要

> 一个 3D 场景图代表着紧凑的场景模型，存储着物体及其之间语义关系的信息，在机器人任务中应用前景良好。与用户交互时，具身智能代理应能回应用户用自然语言提出的关于场景的各类查询。大型语言模型（LLMs）凭借自然语言理解和推理能力，成为用户 - 机器人交互的有效解决方案。近来创建 3D 场景可学习表示的方法已展现出通过适应 3D 世界提升 LLMs 响应质量的潜力。然而，现有方法未明确利用物体间语义关系信息，仅局限于其坐标信息。在本工作中，我们提出 3DGraphLLM 方法构建 3D 场景图的可学习表示。该可学习表示用作 LLMs 的输入以执行 3D 视觉 - 语言任务。在对流行的 ScanRefer、RIORefer、Multi3DRefer、ScanQA、Sqa3D 和 Scan2cap 数据集所做的实验中，我们证明了此方法相较于不使用物体间语义关系信息的基线方法的优势。代码在 https://github.com/CognitiveAISystems/3DGraphLLM 公开可获取。

> A 3D scene graph represents a compact scene model, storing information about the objects and the semantic relationships between them, making its use promising for robotic tasks. When interacting with a user, an embodied intelligent agent should be capable of responding to various queries about the scene formulated in natural language. Large Language Models (LLMs) are beneficial solutions for user-robot interaction due to their natural language understanding and reasoning abilities. Recent methods for creating learnable representations of 3D scenes have demonstrated the potential to improve the quality of LLMs responses by adapting to the 3D world. However, the existing methods do not explicitly utilize information about the semantic relationships between objects, limiting themselves to information about their coordinates. In this work, we propose a method 3DGraphLLM for constructing a learnable representation of a 3D scene graph. The learnable representation is used as input for LLMs to perform 3D vision-language tasks. In our experiments on popular ScanRefer, RIORefer, Multi3DRefer, ScanQA, Sqa3D, and Scan2cap datasets, we demonstrate the advantage of this approach over baseline methods that do not use information about the semantic relationships between objects. The code is publicly available at https://github.com/CognitiveAISystems/3DGraphLLM.

[Arxiv](https://arxiv.org/abs/2412.18450)