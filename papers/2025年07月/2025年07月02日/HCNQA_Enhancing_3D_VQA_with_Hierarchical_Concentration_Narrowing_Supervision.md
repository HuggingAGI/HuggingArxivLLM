# HCNQA：基于分层注意力聚焦监督的三维视觉问答增强方法

发布时间：2025年07月02日

`其他` `计算机视觉`

> HCNQA: Enhancing 3D VQA with Hierarchical Concentration Narrowing Supervision

# 摘要

> 3D视觉问答（3D VQA）对模型理解物理世界和进行空间推理至关重要。基于答案的监督方法是训练3D VQA模型的常用方式，许多采用此方法的模型在任务中表现优异。然而，这种监督方式仅关注模型的最终输出，可能导致模型通过问答对中的常见模式形成浅层捷径。此外，尽管慢思考方法推动了大型语言模型的发展，但它们仍存在思考不足的问题。为解决这些问题，我们提出了	extbf{HCNQA}，一种结合层次化注意力聚焦监督方法的3D VQA模型。通过模拟人类从广泛区域逐步聚焦到具体对象的过程，我们的方法通过层次化监督引导模型完成三个阶段的注意力聚焦。通过监督通用推理路径上的关键节点，我们确保了模型能够发展出合理且有效的推理路径。大量实验结果表明，我们的方法不仅确保了模型发展出合理的推理路径，还显著提升了模型性能。代码可在https://github.com/JianuoZhu/HCNQA获取。

> 3D Visual Question-Answering (3D VQA) is pivotal for models to perceive the physical world and perform spatial reasoning. Answer-centric supervision is a commonly used training method for 3D VQA models. Many models that utilize this strategy have achieved promising results in 3D VQA tasks. However, the answer-centric approach only supervises the final output of models and allows models to develop reasoning pathways freely. The absence of supervision on the reasoning pathway enables the potential for developing superficial shortcuts through common patterns in question-answer pairs. Moreover, although slow-thinking methods advance large language models, they suffer from underthinking. To address these issues, we propose \textbf{HCNQA}, a 3D VQA model leveraging a hierarchical concentration narrowing supervision method. By mimicking the human process of gradually focusing from a broad area to specific objects while searching for answers, our method guides the model to perform three phases of concentration narrowing through hierarchical supervision. By supervising key checkpoints on a general reasoning pathway, our method can ensure the development of a rational and effective reasoning pathway. Extensive experimental results demonstrate that our method can effectively ensure that the model develops a rational reasoning pathway and performs better. The code is available at https://github.com/JianuoZhu/HCNQA.

[Arxiv](https://arxiv.org/abs/2507.01800)