# 电信领域视觉理解能力的衡量：基于VLMs的图像到UML转换性能指标

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Measuring Visual Understanding in Telecom domain: Performance Metrics for Image-to-UML conversion using VLMs

# 摘要

> 电信领域的3GPP文档中满是包含序列图的图像。视觉-语言大模型（VLMs）的进步简化了这类图像到机器可读PlantUML（puml）格式的转换。然而，这类转换的评估仍有不足：现有研究尚未对puml脚本的各类组件进行比较。为此，本研究提出性能指标以衡量这类转换的效果。我们选取3GPP文档中的序列图构建数据集，以模拟特定领域的真实场景。我们将两款VLM（Claude Sonnet与GPT-4V）生成的puml输出与人工标注的真实表示进行对比。借助版本控制工具捕捉差异后，我们引入标准性能指标从多个维度评估准确性，包括参与者识别、消息流准确性、序列顺序及分组结构保留。这些指标能有效量化puml脚本各组件的转换误差。结果显示，节点、边和消息的捕捉准确率较高；但VLMs在处理注释、方框、组等复杂结构时表现欠佳。实验与性能指标均表明，微调VLM时，训练数据需更好地涵盖这些组件。

> Telecom domain 3GPP documents are replete with images containing sequence diagrams. Advances in Vision-Language Large Models (VLMs) have eased conversion of such images to machine-readable PlantUML (puml) formats. However, there is a gap in evaluation of such conversions - existing works do not compare puml scripts for various components. In this work, we propose performance metrics to measure the effectiveness of such conversions. A dataset of sequence diagrams from 3GPP documents is chosen to be representative of domain-specific actual scenarios. We compare puml outputs from two VLMs - Claude Sonnet and GPT-4V - against manually created ground truth representations. We use version control tools to capture differences and introduce standard performance metrics to measure accuracies along various components: participant identification, message flow accuracy, sequence ordering, and grouping construct preservation. We demonstrate effectiveness of proposed metrics in quantifying conversion errors across various components of puml scripts. The results show that nodes, edges and messages are accurately captured. However, we observe that VLMs do not necessarily perform well on complex structures such as notes, box, groups. Our experiments and performance metrics indicates a need for better representation of these components in training data for fine-tuned VLMs.

[Arxiv](https://arxiv.org/abs/2509.11667)